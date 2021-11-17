---
layout: "default"
title: "Kaavatietomallin soveltamisprofiili - asemakaava - ulkoalueet"
description: ""
id: "ulkoalueet"
status: "Ehdotus"
---
# Kaavamääräyslajit - ulkoalueet
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/07>

Ryhmittelyotsikko, vain [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.

1. 
{:toc}

## Vihertehokkuus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0701>

{% include common/clause_start.html type="req" id="prof-ak/vaat-vihertehokuus-maar" %}
Ilmisee, että kaavakohteen suunnittelussa ja toteuttamisessa tulee käyttää [viherkerroinmenetelmää](https://ilmastotyokalut.fi/vihrea-infrastruktuuri/viherkerroinmenetelma/).
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-vihertehokuus-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo), joka kertoo kaavakohteen alueen tonttien viherkertoimen vähimmäisarvon. Numeerisen arvon on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta. Muun tyyppiset arvot eivät ole sallittuja.

Mikäli arvoa ei anneta, tulee noudattaa viherkerroinmenetelmässä määriteltyjä viherkertoimien ehdottomia minitasoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-vihertehokuus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/tip.html content="Viherkerroinmenetelmän viherkerroinluokien minimitasot on kuvattu dokumentin [Viherkerroinmenetelmän kehittäminen Helsingin kaupungille](https://www.ymk-projektit.fi/suunnitteluopas/files/2014/07/Viherkerroin_julkaisu_ymk_08141.pdf) luvussa 3.4.2 Luokkien tavoite- ja minitasot (Julkaisija: Helsingin kaupungin ympäristökeskus, Helsinki 2014)" %}

## Puusto tai kasvillisuus säilytettävä tai korvattava
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0702>

{% include common/clause_start.html type="req" id="prof-ak/vaat-puusto-kasvillisuus-sail-tai-korv-maar" %}
Ilmaisee, että kaavakohteen aluella oleva puusto tai muu kasvillisuus on säilytettävä tai korvattava.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-puusto-kasvillisuus-sail-tai-korv-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-puusto-kasvillisuus-sail-tai-korv-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}


## Olemassa oleva puusto säilytettävä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0703>

{% include common/clause_start.html type="req" id="prof-ak/vaat-puusto-sailytettava-maar" %}
Ilmaisee, että kaavakohteen aluella oleva puusto on säilytettävä.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-puusto-sailytettava-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-puusto-sailytettava-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Maisema säilytettävä avoimena
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0704>

{% include common/clause_start.html type="req" id="prof-ak/vaat-maisema-sailytettava-avoimena-maar" %}
Ilmaisee, että kaavakohteen alueen maisema on säilytettävä avoimena.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-maisema-sailytettava-avoimena-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-maisema-sailytettava-avoimena-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Muu ulkoalueiden toteuttamiseen liittyvä määräys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0705>

{% include common/clause_start.html type="req" id="prof-ak/vaat-muu-ulkoalue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka kuvaa kaavamääräyksen. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-muu-ulkoalue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}



