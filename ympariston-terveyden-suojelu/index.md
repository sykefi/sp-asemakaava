---
layout: "default"
description: ""
id: "ympariston-terveyden-suojelu"
status: "Ehdotus"
---
# Kaavamääräyslajit - ympäristön ja terveyden suojelu
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/13>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

1. 
{:toc}


## Pilaantunut maa-alue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1301>

{% include common/clause_start.html type="req" id="prof-ak/vaat-pilaantunut-maa-alue-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla on ihmisen toiminnan seurauksena haitallisia aineita siinä määrin, että niistä aiheutuu haittaa tai merkittävä riski ympäristölle tai terveydelle, viihtyisyyden vähentymistä tai muuta niihin verrattavissa olevaa haittaa.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-pilaantunut-maa-alue-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa, esimerkiksi lisätietoa pilaantumisen laadusta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-pilaantunut-maa-alue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="rec" id="prof-ak/suos-pilaantunut-maa-alue-liittyva-asiakirja" %}
Mikäli pilaantumiseen liittyen on laadittu selvitys on suositeltavaa linkittää se kaavamääräykseen ```liittyvaAsiakirja```-assosiaation avulla.
{% include common/clause_end.html %}

{% include common/question.html content="Miksi pilaantunut maa-alue on kaavamääräys? Pitäisikö pilaantuneiden maa-alueiden olla osa lähtötietoaineistoja? SYKEn MATTI-järjestelmä?" %}

## Meluaita
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1302>

{% include common/clause_start.html type="req" id="prof-ak/vaat-meluaita-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolle tulee rakentaa meluaita.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-meluaita-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} joka kuvaa aidan vähimmäisääneneristävyyden liikennemelua vastaan desibeleinä (```db```). Numeerisen arvon on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-meluaita-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Meluvalli
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1303>

{% include common/clause_start.html type="req" id="prof-ak/vaat-meluvalli-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolle tulee rakentaa meluvalli.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-meluvalli-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} joka kuvaa vallin vähimmäisääneneristävyyden liikennemelua vastaan desibeleinä (```db```). Numeerisen arvon on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-meluvalli-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Melualue
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1304>

{% include common/clause_start.html type="req" id="prof-ak/vaat-melualue-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla esiintyy siinä määrin melua, että siitä voi aiheutua merkittävää haittaa.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-melualue-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), jolla kuvataan melun tyyppiä ja haitallisuutta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-melualue-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/question.html content="Miksi melualue on kaavamääräys? Pitäisikö melualueiden olla osa lähtötietoaineistoja?" %}

## Radonhaitta huomioitava
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1305>

{% include common/clause_start.html type="req" id="prof-ak/vaat-radonhaitta-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, jolla maaperästä saattaa erittyä radonkaasua siinä määrin, että siitä voi aiheutua terveyshaittaa. Radonhaitta on huomioitava rakennettaessa.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-radonhaitta-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-radonhaitta-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Muu ympäristönsuojeluun liittyvä määräys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1306>

{% include common/clause_start.html type="req" id="prof-ak/vaat-muu-ymparistonsuojelu-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka kuvaa kaavamääräyksen. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-muu-ymparistonsuojelu-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}