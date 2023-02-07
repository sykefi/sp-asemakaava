---
layout: "default"
description: ""
id: "rakennusala-ja-paikka"
status: "Ehdotus"
---
# Kaavamääräykset - Rakennusala ja rakennuspaikka

## Rakennusala
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/rakennusala>

{% include common/clause_start.html type="req" id="sp-ak/vaat-rakennusala-arvot" %}
```arvo```-attribuutin mahdolliset arvot ovat seuraavat:
* Nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} jotka kuvaa rakennusalalle rakennettavaksi tarkoitetun rakennuksen lajin viittaamalla koodistoon [Rakennusluokitus 2018](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712).
* Nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.
{% include common/clause_end.html %}

### Rakennuksen sivu, jossa suora uloskäynti porrashuoneista
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/rakennusalanSivuJossaSuoraUloskayntiPorrashuoneista>

{% include common/clause_start.html type="req" id="sp-ak/vaat-suora-uloskaynti-porrashuoneista-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka kohdalla tulee olla suora uloskäunti porrashuoneista. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

### Ikkunaton seinä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/ikkunatonSeina>

{% include common/clause_start.html type="req" id="sp-ak/vaat-ei-ikkunoita-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka puoleisten rakennusten seiniin ei saa sijoittaa ikkunoita. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

## Rakennuspaikka
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/rakennuspaikka>
{% include common/clause_start.html type="req" id="sp-ak/vaat-rakennuspaikka-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatieto" %} jonka laji on [Käyttötarkoituskohdistus](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/kayttotarkoituskohdistus), jolla on täsmälleen yksi ```arvo``` lajia {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} joka viittaa johonkin [Rakennusluokitus 2018](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712)-koodiston koodiin. Mikäli vähintään yksi lisätieto on annettu, saa rakennuspaikkaan rakentaa vain lisätietojen avulla rajattuja rakennustyyppejä. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

Esimerkkejä:<br>
* ```Asunnon rakennuspaikka``` voidaan määritellä käyttötarkoituskohdistus-lisätiedon Rakennusluokituksen 2018:n mukaisella arvolla [Asuinrakennukset](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712/code/01).

* ```Loma-asunnon rakennuspaikka``` voidaan määritellä käyttötarkoituskohdistus-lisätiedon Rakennusluokituksen 2018:n mukaisella arvolla [Vapaa-ajan asuinrakennukset](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712/code/02).

* ```Saunan rakennuspaikka``` voidaan määritellä käyttötarkoituskohdistus-lisätiedon Rakennusluokituksen 2018:n mukaisella arvolla [Saunarakennukset](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712/code/1910).

* ```Maatalouden talouskeskuksen rakennuspaikka``` voidaan määritellä kahden käyttötarkoituskohdistus-lisätiedon yhdistelmällä, arvoina Rakennusluokituksen 2018:n mukaiset [Asuinrakennukset](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712/code/01) ja [Maatalousrakennukset ja eläinsuojat](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712/code/14) yhdistelmällä.

{% include common/note.html content="Käytetään tavallisesti vain ranta-asemakaavoissa" %}