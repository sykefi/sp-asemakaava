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

## Parvekkeet sijoitettava rungon sisään
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0509>

{% include common/clause_start.html type="req" id="prof-ak/vaat-parvekkeet-rungon-sisaan-maar" %}
Ilmaisee, että kaavakohteen aluella rakennusten parvekkeet tulee rakentaa talon rungon sisään.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-parvekkeet-rungon-sisaan-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka puoleisia sivuja kaavamääräys koskee. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

## Hissi
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0510>

{% include common/clause_start.html type="req" id="prof-ak/vaat-hissi-maar" %}
Ilmaisee, että kaavakohteen aluella rakennuksiin tai niiden tietyille sivuille on rakennettava hissit.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-hissi-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, joka puoleisia sivuja kaavamääräys koskee. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

## Etäisyys naapuritontin rajasta
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0402>

{% include common/clause_start.html type="req" id="prof-ak/vaat-etaisyys-naapuritontin-rajasta-arvot" %}
```arvo```-attribuutin mahdolliset arvot ovat seuraavat:
* Yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} joka kertoo rakennusten vähimmäisetäisyyden naapuritontin rajasta sen kaavakohteen alueella, johon kaavamääräys on liitetty. Numeerisen arvon on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Yksikkönä metri (```m```).
* Nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka puoleista osaa etäisyysvaatimus koskee.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-etaisyys-naapuritontin-rajasta-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Rakennettava kiinni rajaan
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0404>

{% include common/clause_start.html type="req" id="prof-ak/vaat-rakennettava-kiinni-rajaan-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, johon alueen rakennukset tulee rakentaa kiinni. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-rakennettava-kiinni-rajaan-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

<!-- Tätä ei ole nyt koodistoissa. Onko tarpeen? Vastaavia olisi miten paljon. 
## Liitettävä kaukolämpöverkkoon
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/1204>

{% include common/clause_start.html type="req" id="prof-ak/vaat-liitettava-kaukolampoverkkoon-maar" %}
Ilmaisee, että kaavakohde kuvaa alueen, joka on liitettävä kaukolämpöverkkoon.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-liitettava-kaukolampoverkkoon-arvot" %}
```arvo```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-liitettava-kaukolampoverkkoon-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}
-->