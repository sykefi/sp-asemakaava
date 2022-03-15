---
layout: "default"
description: ""
id: "koodistot"
status: "Ehdotus"
---
# Koodistot

## Vuorovaikutustapahtuman laji
{% include common/clause_start.html type="req" id="prof-ak/vaat-vuorovaikutustapahtuman-laji" %}
Luokan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktivuorovaikutustapahtumanlaji" title="AbstraktiVuorovaikutustapahtumanLaji" %} sijaan tulee käyttää tarkentavaa luokkaa {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavanvuorovaikutustapahtumanlaji" title="KaavanVuorovaikutustapahtumanLaji" %}.
{% include common/clause_end.html %}

## Käsittelytapahtuman laji
{% include common/clause_start.html type="req" id="prof-ak/vaat-kasittelytapahtuman-laji" %}
Luokan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktikasittelytapahtumanlaji" title="AbstraktiKasittelytapahtumanLaji" %} sijaan tulee käyttää tarkentavaa luokkaa {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavankasittelytapahtumanlaji" title="KaavanKasittelytapahtumanLaji" %}.
{% include common/clause_end.html %}

## Kaavakohdelaji
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktikaavakohdelaji" title="AbstraktiKaavakohdelaji" %}-koodisto on varattu tulevaisuuden käyttöön. Tässä tietomalliin versiossa ei määritellä asemakaavakohtaista koodistoa kaavakohdelajeille.

{% include common/clause_start.html type="req" id="prof-ak/vaat-kaavakohdelaji" %}
{% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavakohde" title="Kaavakohde" %}-luokan ```laji```-attribuuttia ei saa käyttää informaation välittämiseen. Mikäli sille on annettu ei-tyhjä arvo, se tulee jättää huomiotta.  
{% include common/clause_end.html %}

## Kaavoitusteema
{% include common/clause_start.html type="req" id="prof-ak/vaat-kaavoitusteema" %}
Luokan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktikaavoitusteema" title="AbstraktiKaavoitusteema" %} sijaan tulee käyttää tarkentavaa luokkaa {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavoitusteemaasemakaava" title="KaavoitusteemaAsemakaava" %}.
{% include common/clause_end.html %}

## Kaavamääräyslaji
{% include common/clause_start.html type="req" id="prof-ak/vaat-kaavamaarayslaji" %}
Luokan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktikaavamaarayslaji" title="AbstraktiKaavamaaraysLaji" %} sijaan tulee käyttää tarkentavaa luokkaa {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#kaavamaarayslajiasemakaava" title="KaavamaaraysLajiAsemakaava" %}.
{% include common/clause_end.html %}

## Kaavamääräyksen lisätiedon laji
{% include common/clause_start.html type="req" id="prof-ak/vaat-kaavamaarayksen-lisatieton-laji" %}
Luokan {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#abstraktilisatiedonlaji" title="AbstraktiLisatiedonLaji" %} sijaan tulee käyttää tarkentavaa luokkaa {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatiedonlajiasemakaava" title="LisatiedonLajiAsemakaava" %}.
{% include common/clause_end.html %}

