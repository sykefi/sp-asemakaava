---
layout: "default"
description: ""
id: "sanalliset-maaraykset"
status: "Ehdotus"
---
# Sanallisten kaavamääräysten luokittelu
{:.no_toc}

{:toc}

Sanallisilla kaavamääräyksillä tarkoitetaan kaavamääräystä, jolle on annettu Kaavamääräyksen ```lajin``` lisäksi ```arvo```-attribuutille yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %}.

{% include common/clause_start.html type="req" id="sp-yk/vaat-sanallisten-luokittelu" %}
Sanalliset kaavamääräykset on annotoitava [Sanallisen määräyksen luokka](<http://uri.suomi.fi/codelist/rytj/RY_Sanallisen_Kaavamaarayksen_Luokka/>) -koodein.
{% include common/clause_end.html %}

{% include common/tip.html content="Sanallisten kaavamääräysten luokittelun avulla mahdollistetaan sisällöltään usein hyvin vaihtelevien sanallisten kaavamäärästen älykäs etsittävyys ja luokiteltavuus. Tyypisellisesti seikat, joita ei voida pelkin koodiarvoin kuvata, liittyvät esimerkiksi kaavakohteen toteutustapaan tai jonkin ilmiön erityiseen huomiomiseen." %}

{% include common/question.html content="Tietomallissa on nyt sanallisten luokkia 0-1. Eikö näitä pitäisi voida olla useampia?" %}

### Yleismääräys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Sanallisen_Kaavamaarayksen_Luokka/code/yleismaarays>

{% include common/clause_start.html type="req" id="sp-yk/vaat-yleismaarays" %}
[Yleismääräys](http://uri.suomi.fi/codelist/rytj/RY_Sanallisen_Kaavamaarayksen_Luokka/code/yleismaarays)-koodin avulla annotoidaan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavamaarays" title="Kaavamääräyksiä"%}, jotka liittyvät suoraan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaava" title="Kaavaan"%}.
{% include common/clause_end.html %}