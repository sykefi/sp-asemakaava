---
layout: "default"
description: ""
id: "korkeusasema"
status: "Ehdotus"
---
# Kaavamääräykset - korkeusasema
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/korkeusasema>

1. 
{:toc}

### Korkeusasema

{% include common/clause_start.html type="req" id="prof-ak/vaat-maanpinnan-korkeusasema-konsistenssi" %}
[Maanpinnan korkeusasema](#maanpinnan-korkeusasema) -kaavamääräyksen arvon on vastattava kaavan [Pohjakartta](http://uri.suomi.fi/codelist/rytj/RY_LahtotietoaineistonLaji/code/11)-lajin [Lahtotietoaineiston](../../looginenmallin/dokumentaatio/#lahtotietoaineisto) topografisen aineiston maanpinnan korkeutta kaavakohteen sijannissa kuvaavaa arvoa.
{% include common/clause_end.html %}

## Maanpinnan korkeusasema
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/maanpinnanKorkeusasema>

Kaava-aineistossa voidaan ilmaista maanpinnan nimelliskorkeus merenpinnasta tietyissä pisteissä kaavamääräyksenä, vaikka sen arvon tuleekin perustua kaavan lähtötietoaineiston topografiseen tietoon.

{% include common/clause_start.html type="req" id="prof-ak/vaat-maanpinnan-korkeusasema-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#korkeuspiste" title="Korkeuspiste" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#korkeusvali" title="Korkeusvali" %} jotka kertovat maanpinnan korkeuden merenpinnasta sovitun pystysuuntaisen koordinaatiston arvona kaavakohteen sijainnissa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/question.html content="Miksi maanpinnan korkeusasema on kaavamääräys? Ei voi olla ristiriidassa topografisen pohjakartta-aineiston korkeuskäyrien kanssa?" %}

## Rakennuksen vesikaton ylimmän kohdan korkeusasema
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/vesikatonYlimmanKohdanKorkeusasema>

{% include common/clause_start.html type="req" id="prof-ak/vaat-vesikaton-korkeusasema-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#korkeuspiste" title="Korkeuspiste" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#korkeusvali" title="Korkeusvali" %} jotka kertovat kaavakohteen alueelle sijoitettavien rakennusten vesikaton ylimmän kohdan korkeuden merenpinnasta sovitun pystysuuntaisen koordinaatiston arvona. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

## Rakennuksen julkisivupinnan ja vesikaton leikkauskohdan korkeusasema
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/julkisivupinnanJaVesikatonLeikkauskohdanKorkeusasema>

{% include common/clause_start.html type="req" id="prof-ak/vaat-julkisivupinnan-ja-vesikaton-leikkauksen-korkeusasema-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#korkeuspiste" title="Korkeuspiste" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#korkeusvali" title="Korkeusvali" %} jotka kertovat kaavakohteen alueelle sijoitettavien rakennusten julkisivupinnan ja vesikaton leikkauskohdan korkeuden merenpinnasta sovitun pystysuuntaisen koordinaatiston arvona. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

## Rakennuksen julkisivun enimmäiskorkeus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/julkisivunEnimmaiskorkeus>

{% include common/clause_start.html type="req" id="prof-ak/vaat-julkisivun-enimmaiskorkeus-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} joka kertoo kaavakohteen alueelle sijoitettavien rakennusten julkisivujen minimikorkeuden, maksimikorkeuden tai molemmat. Numeerisen arvon on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Yksikkönä metri (```m```). Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

## Rakennusten, rakenteiden ja laitteiden ylin korkeusasema
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/rakennustenRakenteidenJaLaitteidenYlinKorkeusasema>

{% include common/clause_start.html type="req" id="prof-ak/vaat-rakennusten-rakent-lait-korkeusasema-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#korkeuspiste" title="Korkeuspiste" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#korkeusvali" title="Korkeusvali" %} jotka kertovat kaavakohteen alueelle sijoitettavien rakennusten, rakenteiden ja laitteiden ylimmän korkeuden merenpinnasta sovitun pystysuuntaisen koordinaatiston arvona. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

## Maanalaisen kohteen korkeusasema
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/maanalaisenKohteenKorkeusasema>

{% include common/clause_start.html type="req" id="prof-ak/vaat-maanalaisen-kohteen-korkeusasema-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#korkeuspiste" title="Korkeuspiste" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#korkeusvali" title="Korkeusvali" %} jotka kertovat maanalaisen kaavakohteen perustason korkeuden merenpinnasta sovitun pystysuuntaisen koordinaatiston arvona. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/question.html content="Mitä korkeutta tämä tarkalleen ottaen tarkoittaa? Mikä on oikea termi tälle 'perustasolle'?" %}
