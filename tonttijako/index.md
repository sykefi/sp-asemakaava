---
layout: "default"
description: ""
id: "tonttijako"
status: "Ehdotus"
---
# Kaavamääräyslajit - tonttijako
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/10>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

1. 
{:toc}

## Sivova tonttijako laadittava
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1001>

{% include common/clause_start.html type="req" id="prof-ak/vaat-sitova-tonttijako-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolle on laadittava erillinen sitova tonttijako.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-sitova-tonttijako-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-sitova-tonttijako-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Esitontti
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1001>

{% include common/clause_start.html type="req" id="prof-ak/vaat-esitontti-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, josta on tarkoitus muodostaa tontti.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-esitontti-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tunnusarvo" title="TunnusArvo" %} jotka kuvaavat tulevan tontin pysyviä tunnuksia tietojärjestelmissä tai rekistereissä.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-esitontti-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}