---
layout: "default"
description: ""
id: "yleismaaraykset"
status: "Ehdotus"
---
# Kaavamääräyslajit - yleismääräykset
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/11>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

1. 
{:toc}

## Yleismääräys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1101>

{% include common/clause_start.html type="req" id="prof-ak/vaat-yleismaarays-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka kuvaa kaavamääräyksen. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-yleismaarays-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}


## Ajanmukaisuuden arvioinnin aikaraja
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1102>

{% include common/clause_start.html type="req" id="prof-ak/vaat-ajanmukaiden-arviointi-aikaraja-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä joko
* yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} joka kuvaa sen kaavan hyväksymisestä alkavan ajanjakson pituuden, jonka kuluttua kaavan ajanmukaisuus on arvioitava. Numeerisen arvon  on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#integer" title="Integer" %}-rajapinta. Yksikkönä vuosi (```v```), tai kuukausi (```kk```) tai
* yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#ajanhetkiarvo" title="Ajanhetkiarvo" %} joka kuvaa päivämäärän, johon mennessä kaavan ajanmukaisuus on arvioitava.
Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-ajanmukaiden-arviointi-aikaraja-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Aluetta koskevat sitovat rakentamistapaohjeet
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1103>

{% include common/clause_start.html type="req" id="prof-ak/vaat-sitovat-rakentamistapaohjeet-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jota koskevat sitovat rakentamistapaohjeet.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-sitovat-rakentamistapaohjeet-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-sitovat-rakentamistapaohjeet-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="rec" id="prof-ak/suos-sitovat-rakentamistapaohjeet-liittyva-asiakirja" %}
Rakentamistapaohje on suositeltavaa linkittää kaavamääräykseen ```liittyvaAsiakirja```-assosiaation avulla.
{% include common/clause_end.html %}

## Aluetta koskevat rakentamistapaohjeet
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1104>

{% include common/clause_start.html type="req" id="prof-ak/vaat-ei-sitovat-rakentamistapaohjeet-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jota koskevat ei-sitovat rakentamistapaohjeet.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-ei-sitovat-rakentamistapaohjeet-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-ei-sitovat-rakentamistapaohjeet-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="rec" id="prof-ak/suos-ei-sitovat-rakentamistapaohjeet-liittyva-asiakirja" %}
Rakentamistapaohje on suositeltavaa linkittää kaavamääräykseen ```liittyvaAsiakirja```-assosiaation avulla.
{% include common/clause_end.html %}
