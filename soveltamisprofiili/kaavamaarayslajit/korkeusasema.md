---
layout: "default"
title: "Kaavatietomallin soveltamisprofiili - asemakaava - korkeusasema"
description: ""
id: "korkeusasema"
status: "Ehdotus"
---
# Kaavamääräyslajit - korkeusasema
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/06>

Ryhmittelyotsikko, vain [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.

1. 
{:toc}

## Maanpinnan korkeusasema
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0601>

Kaava-aineistossa voidaan ilmaista maanpinnan nimelliskorkeus merenpinnasta tietyissä pisteissä kaavamääräyksenä, vaikka sen arvon tuleekin perustua kaavan lähtötietoaineiston topografiseen tietoon.

{% include common/clause_start.html type="req" id="prof-ak/vaat-maanpinnan-korkeusasema-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi [Korkeuspiste](../../looginenmalli/dokumentaatio/#korkeuspiste) tai yksi [Korkeusvali](../../looginenmalli/dokumentaatio/#korkeusvali), jotka kertovat maanpinnan korkeuden merenpinnasta sovitun pystysuuntaisen koordinaatiston arvona kaavakohteen sijainnissa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-maanpinnan-korkeusasema-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/question.html content="Miksi maanpinnan korkeusasema on kaavamääräys? Ei voi olla ristiriidassa topografisen pohjakartta-aineiston korkeuskäyrien kanssa?" %}

## Rakennuksen vesikaton ylimmän kohdan korkeusasema
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0602>

{% include common/clause_start.html type="req" id="prof-ak/vaat-vesikaton-korkeusasema-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi [Korkeuspiste](../../looginenmalli/dokumentaatio/#korkeuspiste) tai yksi [Korkeusvali](../../looginenmalli/dokumentaatio/#korkeusvali), jotka kertovat kaavakohteen alueelle sijoitettavien rakennusten vesikaton ylimmän kohdan korkeuden merenpinnasta sovitun pystysuuntaisen koordinaatiston arvona. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-vesikaton-korkeusasema-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}


## Rakennuksen julkisivupinnan ja vesikaton leikkauskohdan korkeusasema
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0603>

{% include common/clause_start.html type="req" id="prof-ak/vaat-julkisivupinnan-ja-vesikaton-leikkauksen-korkeusasema-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi [Korkeuspiste](../../looginenmalli/dokumentaatio/#korkeuspiste) tai yksi [Korkeusvali](../../looginenmalli/dokumentaatio/#korkeusvali), jotka kertovat kaavakohteen alueelle sijoitettavien rakennusten julkisivupinnan ja vesikaton leikkauskohdan korkeuden merenpinnasta sovitun pystysuuntaisen koordinaatiston arvona. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-julkisivupinnan-ja-vesikaton-leikkauksen-korkeusasema-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Rakennuksen julkisivun korkeus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0604>

{% include common/clause_start.html type="req" id="prof-ak/vaat-julkisivun-enimmaiskorkeus-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), joka kertoo kaavakohteen alueelle sijoitettavien rakennusten julkisivujen minimikorkeuden, maksimikorkeuden tai molemmat. Numeerisen arvon on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta. Yksikkönä metri (```m```). Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-julkisivun-enimmaiskorkeus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/note.html content="Koodin otsikko on 'Rakennuksen julkisivun enimmäiskorkeus metreinä' Tässä määräys on yleisempi" %}

## Rakennusten, rakenteiden ja laitteiden ylin korkeusasema
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0605>

{% include common/clause_start.html type="req" id="prof-ak/vaat-rakennusten-rakent-lait-korkeusasema-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi [Korkeuspiste](../../looginenmalli/dokumentaatio/#korkeuspiste) tai yksi [Korkeusvali](../../looginenmalli/dokumentaatio/#korkeusvali), jotka kertovat kaavakohteen alueelle sijoitettavien rakennusten, rakenteiden ja laitteiden ylimmän korkeuden merenpinnasta sovitun pystysuuntaisen koordinaatiston arvona. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-rakennusten-rakent-lait-korkeusasema-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/note.html content="Koodin otsikossa 'Rakennuksen, rakenteiden ja laitteiden...', pitäisi olla kaikki monikossa?" %}

## Maanalaisen kohteen korkeusasema
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0606>

{% include common/clause_start.html type="req" id="prof-ak/vaat-maanalaisen-kohteen-korkeusasema-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi [Korkeuspiste](../../looginenmalli/dokumentaatio/#korkeuspiste) tai yksi [Korkeusvali](../../looginenmalli/dokumentaatio/#korkeusvali), jotka kertovat maanalaisen kaavakohteen perustason korkeuden merenpinnasta sovitun pystysuuntaisen koordinaatiston arvona. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/question.html content="Mitä korkeutta tämä tarkalleen ottaen tarkoittaa? Mikä on oikea termi tälle 'perustasolle'?" %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-maanalaisen-kohteen-korkeusasema-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Muu korkeusasemaan liittyvä määräys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0607>

{% include common/clause_start.html type="req" id="prof-ak/vaat-muu-korkeusasema-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka kuvaa kaavamääräyksen. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-muu-korkeusasema-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}