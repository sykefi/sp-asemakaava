---
layout: "default"
description: ""
id: "lisatiedot"
status: "Ehdotus"
---

# Kaavamääräyksen lisätiedot
{:.no_toc}

## Tyyppi
Kaavamääräyksen tarkempi tyypittely. Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

### Poisluettava käyttötarkoitus
Kaavamääräyksen ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatieto" %} jonka laji on [Poisluettava käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_YK/code/04), ja jonka ```arvo```-attribuutin arvoina on yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} jotka viittaavat [Kaavamääräys](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston koodeihin, jotka sisältyvät ```Käyttötarkoitus```-määrityshierarkiaan. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

Poisluettavat käyttötarkoituslajit tulee valita siten, että ne kohdistuvat ```arvo```-attribuuttien avulla valittuun yleispiirteisempään joukkoon käyttötarkoituksia pois lukien niistä osan.

Esimerkkejä: 
* [Toimitilojen alue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/toimitilojenAlue) pois lukien [Tuotantorakennusten alue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/tuotantorakennustenAlue).

* [Suojavyöhyke](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/toimitilojenAlue) pois lukien [Erityisryhmien asuinrakennusten alue](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/erityisryhmienAsuinrakennustenAlue).
