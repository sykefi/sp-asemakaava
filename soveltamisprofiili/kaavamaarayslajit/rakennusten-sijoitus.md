---
layout: "default"
title: "Kaavatietomallin soveltamisprofiili - asemakaava - rakennusten sijoitus"
description: ""
id: "rakennusten-sijoitus"
status: "Ehdotus"
---
# Kaavamääräyslajit - rakennusten sijoitus
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/04>

Ryhmittelyotsikko, vain [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.

1. 
{:toc}

## Rakentamisen suhde alueen pinta-alaan
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0401>

{% include common/clause_start.html type="req" id="prof-ak/vaat-rak-suhde-alueen-pinta-alaan-arvot" %}
```arvo```-attribuutin arvona saa esiintyä joko yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) tai yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), joka kertoo kuinka suuren osan sen kaavakohteen pinta-alasta, johon kaavamääräys on liitetty, saa käyttää rakentamiseen. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta. Ilmaistaan prosenttilukuna (```%```). Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-rak-suhde-alueen-pinta-alaan-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Etäisyys naapuritontin rajasta
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0402>

{% include common/clause_start.html type="req" id="prof-ak/vaat-etaisyys-naapuritontin-rajasta-arvot" %}
```arvo```-attribuutin mahdolliset arvot ovat seuraavat:
* Yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo), joka kertoo rakennusten vähimmäisetäisyyden naapuritontin rajasta sen kaavakohteen alueella, johon kaavamääräys on liitetty. Numeerisen arvon on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta. Yksikkönä metri (```m```).
* Nolla tai useampi [GeometriaArvo](../../looginenmalli/dokumentaatio/#geometriaarvo), joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka puoleista osaa etäisyysvaatimus koskee.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-etaisyys-naapuritontin-rajasta-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Rakennusala
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0403>

{% include common/clause_start.html type="req" id="prof-ak/vaat-rakennusala-maar" %}
Ilmaisee, että kaavakohteen alue on rakennusala. Mikäli rakennusaloja on määritelty jonkin suuremman kaavakohteen alueen sisälle, tulee rakennukset suuremman kaavakohteen alueella rakentaa siten, että ne sijoittuvat kokonaan jokin rakennusalan sisälle.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-rakennusala-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), jotka kuvaa rakennusalalle rakennettavaksi tarkoitetun rakennuksen lajin viittaamalla koodistoon [Rakennusluokitus 2018](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712).
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-rakennusala-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Rakennettava kiinni rajaan
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0404>

{% include common/clause_start.html type="req" id="prof-ak/vaat-rakennettava-kiinni-rajaan-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [GeometriaArvo](../../looginenmalli/dokumentaatio/#geometriaarvo), joka on päällekkäin sen kaavakohteen geometrian osan kanssa, johon alueen rakennukset tulee rakentaa kiinni. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-rakennettava-kiinni-rajaan-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Rakennuspaikka
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0405>

{% include common/clause_start.html type="req" id="prof-ak/vaat-rakennuspaikka-maar" %}
Ilmaisee, että kaavakohteen geometria kuvaa paikkaa, jolla on rakennus tai johon voidaan rakentaa yksi tai useampi rakennus.
{% include common/clause_end.html %}

{% include common/question.html.html content="Voiko yhteen rakennuspaikkaan rakentaa useamman rakennuksen?" %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-rakennuspaikka-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-rakennuspaikka-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), jonka laji on [Käyttötarkoituskohdistus](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/02), jolla on täsmälleen yksi ```arvo``` lajia [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), joka viittaa johonkin [Rakennusluokitus 2018](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712)-koodiston koodiin. Muun tyyppiset arvot eivät ole sallittuja.

Mikäli vähintään yksi lisätieto on annettu, saa rakennuspaikkaan rakentaa vain lisätietojen avulla rajattuja rakennustyyppejä.
{% include common/clause_end.html %}

{% include common/note.html.html content="Käytetään tavallisesti vain ranta-asemakaavoissa" %}

## Muu rakennusten sijoitukseen liittyvä määräys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0406>

{% include common/clause_start.html type="req" id="prof-ak/vaat-muu-rakennusten-sijoitus-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-muu-rakennusten-sijoitus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}