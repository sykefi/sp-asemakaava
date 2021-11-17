---
layout: "default"
title: "Kaavatietomallin soveltamisprofiili - asemakaava"
description: ""
id: "kayttotarkoitukset"
status: "Ehdotus"
---
# Kaavamääräyslajit - käyttötarkoitukset
{:.no_toc}

1. 
{:toc}

## Alueen käyttötarkoitus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01>

Ryhmittelyotsikko, vain koodin [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.

{% include common/clause_start.html type="req" id="prof-ak/vaat-alueen-kayttotarkoitus" %}
Kaikkien asemakaavojen tietoaineistojen sisältämien [Kaavamaarays](../../looginenmalli/dokumentaatio/#kaavamaarays)-luokan instanssien, joiden ```laji```-attribuutin arvo on jokin [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01)-koodin alakoodi, osalta tulee noudattaa seuraavia rajoituksia:
* ```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
* ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), jonka laji on [Poisluettava käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/04), ja jonka ```arvo```-attribuutin arvoina on yksi tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), jotka viittaavat koodiston [KaavamääraysLaji](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) koodien [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) tai [Alueen osan käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/02) alakoodeihin. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

Poisluettavat käyttötarkoituslajit tulee valita siten, että ne kohdistuvat ```arvo```-attribuuttien avulla valittuun yleispiirteisempään joukkoon käyttötarkoituksia poislukien niistä osan. Esim. [Työ ja tuotanto](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0106) poislukien [Alue, jolle saa sijoittaa merkittävän, vaarallisia kemikaaleja valmistavan tai varastoivan laitoksen](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/010604).

{% include common/question.html content="Tulisiko olla oma lisätiedon laji 'Käyttötarkoituksen osuus maapinta-alasta', jonka avulla voitaisiin määrätä käyttötarkoituksen jakautuminen tapauksissa, josssa kyse ei ole rakentamisesta tai kun sallittua kerrosalaa tai -tilavuutta ei määrätä kaavassa?" %}


## Alueen osan käyttötarkoitus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/02>

Ryhmittelyotsikko, vain [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.

{% include common/clause_start.html type="req" id="prof-ak/vaat-alueen-osan-kayttotarkoitus" %}
Kaikkien asemakaavojen tietoaineistojen sisältämien [Kaavamaarays](../../looginenmalli/dokumentaatio/#kaavamaarays)-luokan instanssien, joiden ```laji```-attribuutin arvo on jokin [Alueen osan käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/02)-koodin alakoodi, osalta tulee noudattaa seuraavia rajoituksia:
* ```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
* ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), jonka laji on [Poisluettava käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/04), ja jonka ```arvo```-attribuutin arvoina on yksi tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), jotka viittaavat koodiston [KaavamääraysLaji](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) koodin [Alueen osan käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/02) alakoodeihin. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

Poisluettavat käyttötarkoituslajit tulee valita siten, että ne kohdistuvat ```arvo```-attribuuttien avulla valittuun yleispiirteisempään joukkoon käyttötarkoituksia poislukien niistä osan.

{% include common/question.html content="Tulisiko olla oma lisätiedon laji 'Käyttötarkoituksen osuus maapinta-alasta', jonka avulla voitaisiin määrätä käyttötarkoituksen jakautuminen tapauksissa, josssa kyse ei ole rakentamisesta tai kun sallittua kerrosalaa tai -tilavuutta ei määrätä kaavassa?" %}
