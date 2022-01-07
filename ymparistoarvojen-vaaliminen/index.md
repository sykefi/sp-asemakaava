---
layout: "default"
description: ""
id: "ymparistoarvojen-vaaliminen"
status: "Ehdotus"
---
# Kaavamääräyslajit - ympäristöarvojen vaaliminen
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/09>

Ryhmittelyotsikko, vain [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.

1. 
{:toc}

## Kulttuurihistoriallisesti arvokas alue tai kohde
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0901>

{% include common/clause_start.html type="req" id="prof-ak/vaat-kulttuurihist-merkittava-alue" %}
Kaikkien asemakaavojen tietoaineistojen sisältämien [Kaavamaarays](../../looginenmalli/dokumentaatio/#kaavamaarays)-luokan instanssien, joiden ```laji```-attribuutin arvo on jokin [Kultturihistoriallisesti arvokas alue tai kohde](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0901)-koodin alakoodi, osalta tulee noudattaa seuraavia rajoituksia:
* ```arvo```-attribuutin arvona saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
* ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), joka ```laji``` on yksi seuraavista:   
   * [Kulttuurihistoriallinen merkittävyys](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/05), jonka arvoina on yksi tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), jotka viittaavat johonkin [Kulttuurihistoriallinen merkittävyys](http://uri.suomi.fi/codelist/rakrek/kulthistmer) koodiston koodeista,
   * [Kulttuurihistoriallinen arvotyyppi](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/06), jonka arvoina on yksi tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), jotka viittaavat johonkin [Kulttuurihistoriallinen arvotyyppi](http://uri.suomi.fi/codelist/rakrek/Kulthistatyyp) koodiston koodeista,
   * [Kulttuurihistoriallinen tyyppi](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/07), jonka arvoina on yksi tai useampi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), jotka viittaavat johonkin [Kulttuurihistoriallinen tyyppi](http://uri.suomi.fi/codelist/rakrek/kulthistyyp) koodiston koodeista, tai
   * [Kulttuurihistoriallisen merkittävyyden kriteerit](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/08), jonka arvoina on yksi tai useampi[KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), joka viittaa johonkin [Kulttuurihistoriallisen merkittävyyden kriteerit](http://uri.suomi.fi/codelist/rakrek/KultKritee) koodiston koodeista.
Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/question.html content="Kulttuurihistoriallisen merkittävyyden kriteerit on monikossa, kun muut koodien otsikot ovat yksikössä, pitäisikö myös se vaihtaa yksikköön? Samat nimet ovat käytössä viitatuissa rakrek-koodistoissa." %}

{% include common/question.html content="Tämä pääluokka toimii nyt kaatoluokkana, koska sitä ei ole rajattu vain ryhmittelyotsikoksi. Onko tämä tarkoitus?" %}

### Suojeltava alue tai alueen osa
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/090101>

{% include common/clause_start.html type="req" id="prof-ak/vaat-suojeltava-alue" %}
Ilmaisee, että kaavakohde kuvaa suojeltavan alueen tai alueen osan.
{% include common/clause_end.html %}

### Suojeltava rakennus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/090102>

{% include common/clause_start.html type="req" id="prof-ak/vaat-suojeltava-rakennus-maar" %}
Ilmaisee, että kaavakohde kuvaa suojeltavan [rakennuksen](http://uri.suomi.fi/terminology/rakymp/c6).
{% include common/clause_end.html %}

### Suojeltava rakennelma
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/090103>

{% include common/clause_start.html type="req" id="prof-ak/vaat-suojeltava-rakennelma-maar" %}
Ilmaisee, että kaavakohde kuvaa suojeltavan [rakennelman](http://uri.suomi.fi/terminology/mrl/concept-125).
{% include common/clause_end.html %}

### Kiinteä suojeltava kohde
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/090104>

{% include common/clause_start.html type="req" id="prof-ak/vaat-kiintea-suojeltava-kohde-maar" %}
Ilmaisee, että kaavakohde kuvaa kiinteän suojeltavan kohteen.
{% include common/clause_end.html %}

### Kiinteä muinaisjäännös
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/090105>

{% include common/clause_start.html type="req" id="prof-ak/vaat-kiintea-muinaisjaannos-maar" %}
Ilmaisee, että kaavakohde kuvaa kiinteän muinaisjäännöksen.
{% include common/clause_end.html %}

## Luontoarvoiltaan arvokas alue tai kohde
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0902>

{% include common/clause_start.html type="req" id="prof-ak/vaat-kulttuurihist-merkittava-alue" %}
Kaikkien asemakaavojen tietoaineistojen sisältämien [Kaavamaarays](../../looginenmalli/dokumentaatio/#kaavamaarays)-luokan instanssien, joiden ```laji```-attribuutin arvo on jokin [Luontoarvoiltaan arvokas alue tai kohde](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0902)-koodin alakoodi, osalta tulee noudattaa seuraavia rajoituksia:
* ```arvo```-attribuutin arvona saa esiintyä nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
* ```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), joka ```laji``` on yksi seuraavista:   
   * [Ympäristöarvon peruste](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/09), jolla on yksi arvona yksi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo), joka kuvaa ympäristöarvon perusteen sanallisesti, tai
   * [Ympäristö- tai luontoarvon merkittävyys](http://uri.suomi.fi/codelist/rytj/RY_LisatiedonLaji_AK/code/10), on yksi arvona yksi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo), joka kuvaa ympäristö- tai luontoarvon merkittävyyden sanallisesti.

Muun tyyppiset lisätietojen arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/note.html content="Mikäli ympäristöarvojen perusteet ja merkittävyydet kuvataan tulevaisuudessa omina koodistoinaan, tulee lisätietojen sallittuja arvoja muuttaa viittaamaan niihin" %}

{% include common/question.html content="Tämä pääluokka toimii nyt kaatoluokkana, koska sitä ei ole rajattu vain ryhmittelyotsikoksi. Onko tämä tarkoitus?" %}

### Suojeltu puu
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/090201>

{% include common/clause_start.html type="req" id="prof-ak/vaat-suojeltu-puu-maar" %}
Ilmaisee, että kaavakohde kuvaa suojellun puun.
{% include common/clause_end.html %}

{% include common/question.html content="Onko koodi tarkoituksella nimenomaan suojeltu, eikä suojeltava?" %}

### Säilytettävä puu
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/090202>

{% include common/clause_start.html type="req" id="prof-ak/vaat-sailytettava-puu-maar" %}
Ilmaisee, että kaavakohde kuvaa säilytettävän puun.
{% include common/clause_end.html %}

### Suojeltava vesistö tai vesialue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/090203>

{% include common/clause_start.html type="req" id="prof-ak/vaat-suojeltava-vesisto-maar" %}
Ilmaisee, että kaavakohde kuvaa suojeltavan vesistön tai vesialueen.
{% include common/clause_end.html %}

### Luonnon monimuotoisuuden kannalta tärkeä alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/090204>

{% include common/clause_start.html type="req" id="prof-ak/vaat-luonnon-monimuotoisuus-maar" %}
Ilmaisee, että kaavakohde kuvaa luonnon monimuotoisuuden kannalta tärkeän alueen.
{% include common/clause_end.html %}

### Ekologinen yhteys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/090205>

{% include common/clause_start.html type="req" id="prof-ak/vaat-ekologinen-yhteys-maar" %}
Ilmaisee, että kaavakohde kuvaa ekologisen yhteyden.
{% include common/clause_end.html %}

## Alue, jolla ympäristö säilytetään
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0903>

{% include common/clause_start.html type="req" id="prof-ak/vaat-sailytettava-ymparisto-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla ympäristö säilytetään.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-sailytettava-ymparisto-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-sailytettava-ymparisto-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Alue, jolla on erityistä ulkoilun ohjaamistarvetta
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0904>

{% include common/clause_start.html type="req" id="prof-ak/vaat-ulkoilun-ohjaamistarve-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla on sen luontoarvojen vuoksi erityistä ulkoilun ohjaamistarvetta.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-ulkoilun-ohjaamistarve-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-ulkoilun-ohjaamistarve-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}