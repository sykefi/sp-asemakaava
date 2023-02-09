---
layout: "default"
description: ""
id: "lisatiedot"
status: "Ehdotus"
---

# Kaavamääräyksen lisätiedot
{:.no_toc}

{% include common/clause_start.html type="req" id="sp-ak/vaat-kaavamaarayksen-lisatieto" %}
Kaavamääräyksen lisätiedot ovat kaavamääräystä täsmentäviä tietoja, jotka ei voida käyttää yksinään. Kaavamääräyksen lisätiedon on siis liityttävä kaavamääräykseen.

## Tyyppi
Kaavamääräyksen tarkempi tyypittely. Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

### Poisluettava käyttötarkoitus
Kaavamääräyksen ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatieto" %} jonka laji on [Poisluettava käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/poisluettavaKayttotarkoitus), ja jonka ```arvo```-attribuutin arvoina on yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} jotka viittaavat [Kaavamääräys](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston koodeihin, jotka sisältyvät ```Käyttötarkoitus```-määrityshierarkiaan. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

Poisluettavat käyttötarkoituslajit tulee valita siten, että ne kohdistuvat ```arvo```-attribuuttien avulla valittuun yleispiirteisempään joukkoon käyttötarkoituksia pois lukien niistä osan.

Esimerkkejä: 
* [Toimitilojen alue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/toimitilojenAlue) pois lukien [Tuotantorakennusten alue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/tuotantorakennustenAlue).

* [Suojavyöhyke](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/toimitilojenAlue) pois lukien [Erityisryhmien asuinrakennusten alue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/erityisryhmienAsuinrakennustenAlue).

### Informatiivinen
Kaavamääräyksen lisätiedolla [Informatiivinen](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/informatiivinen) voidaan merkitä luonteeltaan informatiiviset kaavamääräykset. Tällä tarkoitetaan lähtökohtaisesti muiden viranomaisten maankäyttöön liittyviin päätöksiin tai lainsäädäntöön, sekä maakunnallisiin tai valtakunnallisiin selvityksiin ja inventointeihin perustuvia kaavakohteita, joihin ei ole kaavasuunnitelmassa liitetty täydentäviä kaavamääräyksiä.

## Rakentamisen ohjaus

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

### Rakentamistapaohje huomioitava
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/rakentamistapaOhjeHuomioitava>

{% include common/clause_start.html type="rec" id="sp-ak/suos-sitovat-rakentamistapaohjeet-liittyva-asiakirja" %}
Rakentamistapaohje on suositeltavaa linkittää kaavamääräykseen ```liittyvaAsiakirja```-assosiaation avulla.
{% include common/clause_end.html %}

<!--
### Liitettävä kaukolämpöverkkoon
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/liitettavaKaukolampoverkkoon>
-->

<!-->
## Rakennettava kiinni rajaan
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0404>

{% include common/clause_start.html type="req" id="sp-ak/vaat-rakennettava-kiinni-rajaan-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, johon alueen rakennukset tulee rakentaa kiinni. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}
-->
<!--
## Parvekkeet sijoitettava rungon sisään
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0509>

{% include common/clause_start.html type="req" id="sp-ak/vaat-parvekkeet-rungon-sisaan-maar" %}
Ilmaisee, että kaavakohteen aluella rakennusten parvekkeet tulee rakentaa talon rungon sisään.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-ak/vaat-parvekkeet-rungon-sisaan-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka puoleisia sivuja kaavamääräys koskee. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}
-->
<!--
## Hissi
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0510>

{% include common/clause_start.html type="req" id="sp-ak/vaat-hissi-maar" %}
Ilmaisee, että {% include common/moduleLink.html moduleId="kaavatiedot" path="dokumentaatio/#kaavakohde" title="Kaavakohteen" %} aluella rakennuksiin tai niiden tietyille sivuille on rakennettava hissit.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-ak/vaat-hissi-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, joka puoleisia sivuja kaavamääräys koskee. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}
-->