---
layout: "default"
description: ""
id: "rakentamistapa"
status: "Ehdotus"
---
# Kaavamääräyslajit - rakentamistapa
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/05>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

1. 
{:toc}

## Kattokaltevuus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0501>

{% include common/clause_start.html type="req" id="prof-ak/vaat-kattokaltevuus-arvot" %}
```arvo```-attribuutin arvoja saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} joka kertoo rakennusten katon sallitun kaltevuuden asteina (```deg```) sen kaavakohteen alueella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-kattokaltevuus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Uloke
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0502>

{% include common/clause_start.html type="req" id="prof-ak/vaat-uloke-maar" %}
Ilmaisee, että kaavakohteen geometria kuvaa liikenne- rautatie- tai katualueen osaa, johon saa sijoittaa yläpuolisen rakentamisen vaatimia kantavia rakenteita, jotka eivät haittaa liikennealueen käyttöä.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-uloke-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-uloke-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Rakennuksen harjasuunta
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0503>

{% include common/clause_start.html type="req" id="prof-ak/vaat-harjasuunta-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} jotka kertovat rakennusten katon harjan sallitun kompassisuunnan asteina (```deg```) sen kaavakohteen alueella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-harjasuunta-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Kulkuaukko
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0504>

{% include common/clause_start.html type="req" id="prof-ak/vaat-kulkuaukko-maar" %}
Ilmaisee, että kaavakohteen geometria kuvaa rakennukseen liittyvää paikkaa, johon tulee jättää kulkuaukko.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-kulkuaukko-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-kulkuaukko-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Valokatteinen tila
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0505>

{% include common/clause_start.html type="req" id="prof-ak/vaat-valokatteinen-tila-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-valokatteinen-tila-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Suora uloskäynti porrashuoneista
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0506>

{% include common/clause_start.html type="req" id="prof-ak/vaat-suora-uloskaynti-porrashuoneista-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka kohdalla tulee olla suora uloskäunti porrashuoneista. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-suora-uloskaynti-porrashuoneista-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Ikkunaton seinä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/ikkunatonSeina>

{% include common/clause_start.html type="req" id="prof-ak/vaat-ei-ikkunoita-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka puoleisten rakennusten seiniin ei saa sijoittaa ikkunoita. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-ei-ikkunoita-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Ääneneristävyys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0508>

{% include common/clause_start.html type="req" id="prof-ak/vaat-aaneneristavyys-arvot" %}
```arvo```-attribuutin mahdolliset arvot ovat seuraavat:
* Yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} joka kuvaa rakennuksen ulkoseinien sekä ikkunoiden ja muiden rakenteiden vähimmäisääneneristävyyden liikennemelua vastaan desibeleinä (```db```). Numeerisen arvon on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta.
* Nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka puoleisia sivuja kaavamääräys koskee.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-aaneneristavyys-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Parvekkeet sijoitettava rungon sisään
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0509>

{% include common/clause_start.html type="req" id="prof-ak/vaat-parvekkeet-rungon-sisaan-maar" %}
Ilmaisee, että kaavakohteen aluella rakennusten parvekkeet tulee rakentaa talon rungon sisään.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-parvekkeet-rungon-sisaan-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka puoleisia sivuja kaavamääräys koskee. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-parvekkeet-rungon-sisaan-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Hissi
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0510>

{% include common/clause_start.html type="req" id="prof-ak/vaat-hissi-maar" %}
Ilmaisee, että kaavakohteen aluella rakennuksiin tai niiden tietyille sivuille on rakennettava hissit.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-hissi-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, joka puoleisia sivuja kaavamääräys koskee. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-hissi-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Viherkatto
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/viherkatto>

{% include common/clause_start.html type="req" id="prof-ak/vaat-viherkatto-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %} (yksi kullakin kielellä), joka täydentää kaavamääräystietoa. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-viherkatto-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}
