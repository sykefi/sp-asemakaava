---
layout: "default"
description: ""
id: "laatusaannot"
status: "Ehdotus"
---
# Laatusäännöt

Nämä laatusäännöt laajentavat Kaavatietomallin [yleisiä laatusääntöjä](https://tietomallit.ymparisto.fi/kaavatiedot/v1.1/looginenmalli/laatusaannot.html).

### Käyttötarkoitusalueet

{% include common/clause_start.html type="req" id="prof-ak/vaat-kayttotarkoitusalue-maar" %}
Asemakaavan käyttötarkoitusalueella tarkoitetaan [Kaavakohde](dokumentaatio/#kaavakohde)-luokan objektia, joka liittyy assosiaatiolla ```maarays``` yhteen tai useampaan sellaiseen [Kaavamaarays](dokumentaatio/#kaavamaarays)-luokan objektiin, jonka ```laji```-attribuutin arvo on jokin [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji/code/)-koodiston arvoista.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-aluemainen-kayttotarkoitusalue" %}
Asemakaavan käyttötarkoitusalueiden ```geometria```-attribuutin kuvaamaan geometrian tulee olla aluemainen.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-ei-leikkaavat-kayttotarkoitusalueet" %}
Asemakaavan käyttötarkoitusalueet eivät saa leikata toisiaan. Toisin sanoen alueet eivät saa sijaita spatiaalisesti päällekkäin.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-asemakaavan-kayttotarkoituspeite" %}
Asemakaavan, jonka ```elinkaaritila```-attribuutin arvo on kaavaehdotus tai myöhempi (Kaavaehdotus, Tarkistettu kaavaehdotus, Hyväksytty kaava, Oikaisukehotuksen alainen, Valituksen alainen, Osittain voimassa, Voimassa, Kumottu tai Kumoutunut), sisältämien käyttötarkoitusalueiden tulee peittää sen ```aluerajaus```-attribuutin ilmaisema kaavan alue siten, että jokainen alueen sisäinen sijaintipiste sisältyy täsmälleen yhteen käyttötarkoitusalueeseen.
{% include common/clause_end.html %}