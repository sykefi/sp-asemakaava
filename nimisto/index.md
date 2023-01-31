---
layout: "default"
description: ""
id: "nimisto"
status: "Ehdotus"
---
# Kaavamääräyslajit - nimistö
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/14>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

{% include common/question.html content="Onko jossakin päätetty, miten kielisyys nimissä hoidetaan, nyt voi esittää useampia arvoja? Onko oletettu että arvoksi laitetaan jokin objekti, joka sisältää LanguageString-tyyppiset kielisyystiedot?" %}

1. 
{:toc}

## Kadun tai tien nimi
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/kadunTaiTienNimi>

{% include common/clause_start.html type="req" id="prof-ak/vaat-kadun-tien-nimi-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), jolla annetaan kaavakohteen kuvaaman kadun tai tien nimi. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-kadun-tien-nimi-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Torin tai aukion nimi
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/torinTaiKatuaukionNimi>

{% include common/clause_start.html type="req" id="prof-ak/vaat-torin-aukion-nimi-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), jolla annetaan kaavakohteen kuvaaman torin tai aukion nimi. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-torin-aukion-nimi-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Puiston tai muun yleisen alueen nimi
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/puistonTaiMuunYleisenAlueenNimi>

{% include common/clause_start.html type="req" id="prof-ak/vaat-yleisen-alueen-nimi-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), jolla annetaan kaavakohteen kuvaaman torin tai aukion nimi. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-yleisen-alueen-nimi-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Kaupungin- tai kunnanosan nimi
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/kaupunginTaiKunnanosanNimi>

{% include common/clause_start.html type="req" id="prof-ak/vaat-kaupungin-kunnan-osan-nimi-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), jolla annetaan kaavakohteen kuvaaman kaupungin- tai kunnanosan nimi. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-kaupungin-kunnan-osan-nimi-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Korttelin numero
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji/code/korttelinNumero>

{% include common/clause_start.html type="req" id="prof-ak/vaat-korttelinumero-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} jolla annetaan kaavakohteen kuvaaman korttelin korttelinumero. Numeerisen arvon on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#integer" title="Integer" %}-rajapinta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-korttelinumero-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}