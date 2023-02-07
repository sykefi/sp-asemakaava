---
layout: "default"
description: ""
id: "kayttotarkoitukset"
status: "Ehdotus"
---
# Kaavamääräyslajit - käyttötarkoitukset

## Alueen käyttötarkoitus

{% include common/clause_start.html type="req" id="sp-ak/vaat-aluemainen-kayttotarkoitusalue" %}
Asemakaavan käyttötarkoitusalue on {% include common/moduleLink.html moduleId="kaavatiedot" path="dokumentaatio/#kaavakohde" title="Kaavakohde" %}-luokan objekti, jonka ```geometria```-attribuutin kuvaama geometria on aluemainen.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-ak/vaat-kayttotarkoitusalue-maar" %}
Asemakaavan käyttötarkoitusalue liittyy assosiaatiolla ```maarays``` yhteen tai useampaan sellaiseen [Kaavamaarays](dokumentaatio/#kaavamaarays)-luokan objektiin, jonka ```laji```-attribuutin arvo on jokin [Kaavamääräys](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston arvoista, joka sisältyy määrityshierarkioihin  ```Käyttötarkoitus``` ja ```Asemakaava```.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-ak/vaat-ei-leikkaavat-kayttotarkoitusalueet" %}
Asemakaavan käyttötarkoitusalueet eivät saa leikata toisiaan. Toisin sanoen alueet eivät saa sijaita spatiaalisesti päällekkäin.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-ak/vaat-asemakaavan-kayttotarkoituspeite" %}
Asemakaavan, jonka ```elinkaaritila```-attribuutin arvo on kaavaehdotus tai myöhempi (Kaavaehdotus, Tarkistettu kaavaehdotus, Hyväksytty kaava, Oikaisukehotuksen alainen, Valituksen alainen, Osittain voimassa, Voimassa, Kumottu tai Kumoutunut), sisältämien käyttötarkoitusalueiden tulee peittää sen ```aluerajaus```-attribuutin ilmaisema kaavan alue siten, että jokainen alueen sisäinen sijaintipiste sisältyy täsmälleen yhteen käyttötarkoitusalueeseen.
{% include common/clause_end.html %}

## Alueen osa

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/code/osaAlue>
{% include common/clause_start.html type="req" id="sp-ak/vaat-aluemainen-osaalue" %}
Asemakaavan alueen osa on {% include common/moduleLink.html moduleId="kaavatiedot" path="dokumentaatio/#kaavakohde" title="Kaavakohde" %}-luokan objekti, jonka ```geometria```-attribuutin kuvaama geometria on aluemainen.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="sp-ak/vaat-osaalue-maar" %}
Asemakaavan käyttötarkoitusalue liittyy assosiaatiolla ```maarays``` yhteen tai useampaan sellaiseen [Kaavamaarays](dokumentaatio/#kaavamaarays)-luokan objektiin, jonka ```laji```-attribuutin arvo on jokin [Kaavamääräys](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodiston arvoista, joka sisältyy määrityshierarkioihin  ```Käyttötarkoitus``` ja ```Asemakaava```.
{% include common/clause_end.html %}