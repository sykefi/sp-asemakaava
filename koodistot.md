---
layout: "default"
description: ""
id: "koodistot"
status: "Ehdotus"
---
# Koodistot

## Vuorovaikutustapahtuman laji
{% include common/clause_start.html type="req" id="prof-ak/vaat-vuorovaikutustapahtuman-laji" %}
Luokan [AbstraktiVuorovaikutustapahtumanLaji](../../looginenmalli/dokumentaatio/#abstraktivuorovaikutustapahtumanlaji) sijaan tulee käyttää tarkentavaa luokkaa [KaavanVuorovaikutustapahtumanLaji](../../looginenmalli/dokumentaatio/#kaavanvuorovaikutustapahtumanlaji).
{% include common/clause_end.html %}

## Käsittelytapahtuman laji
{% include common/clause_start.html type="req" id="prof-ak/vaat-kasittelytapahtuman-laji" %}
Luokan [AbstraktiKasittelytapahtumanLaji](../../looginenmalli/dokumentaatio/#abstraktikasittelytapahtumanlaji) sijaan tulee käyttää tarkentavaa luokkaa [KaavanKasittelytapahtumanLaji](../../looginenmalli/dokumentaatio/#kaavankasittelytapahtumanlaji).
{% include common/clause_end.html %}

## Kaavakohdelaji
[AbstraktiKaavakohdelaji](../../looginenmalli/dokumentaatio/#abstraktikaavakohdelaji)-koodisto on varattu tulevaisuuden käyttöön. Tässä tietomalliin versiossa ei määritellä asemakaavakohtaista koodistoa kaavakohdelajeille.

{% include common/clause_start.html type="req" id="prof-ak/vaat-kaavakohdelaji" %}
[Kaavakohde](../../looginenmalli/dokumentaatio/#kaavakohde)-luokan ```laji```-attribuuttia ei saa käyttää informaation välittämiseen. Mikäli sille on annettu ei-tyhjä arvo, se tulee jättää huomiotta.  
{% include common/clause_end.html %}

## Kaavoitusteema
{% include common/clause_start.html type="req" id="prof-ak/vaat-kaavoitusteema" %}
Luokan [AbstraktiKaavoitusteema](../../looginenmalli/dokumentaatio/#abstraktikaavoitusteema) sijaan tulee käyttää tarkentavaa luokkaa [KaavoitusteemaAsemakaava](../../looginenmalli/dokumentaatio/#kaavoitusteemaasemakaava).
{% include common/clause_end.html %}

## Kaavamääräyslaji
{% include common/clause_start.html type="req" id="prof-ak/vaat-kaavamaarayslaji" %}
Luokan [AbstraktiKaavamaaraysLaji](../../looginenmalli/dokumentaatio/#abstraktikaavamaarayslaji) sijaan tulee käyttää tarkentavaa luokkaa [KaavamaaraysLajiAsemakaava](../../looginenmalli/dokumentaatio/#kaavamaarayslajiasemakaava).
{% include common/clause_end.html %}

## Kaavamääräyksen lisätiedon laji
{% include common/clause_start.html type="req" id="prof-ak/vaat-kaavamaarayksen-lisatieton-laji" %}
Luokan [AbstraktiLisatiedonLaji](../../looginenmalli/dokumentaatio/#abstraktilisatiedonlaji) sijaan tulee käyttää tarkentavaa luokkaa [LisatiedonLajiAsemakaava](../../looginenmalli/dokumentaatio/#lisatiedonlajiasemakaava).
{% include common/clause_end.html %}

