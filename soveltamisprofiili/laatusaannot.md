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
Asemakaavan käyttötarkoitusalue on [Kaavakohde](dokumentaatio/#kaavakohde)-luokan objekti, joka liittyy assosiaatiolla ```maarays``` yhteen tai useampaan sellaiseen [Kaavamaarays](dokumentaatio/#kaavamaarays)-luokan objektiin, jonka ```laji```-attribuutin arvo on jokin [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01)-koodin alakoodeista.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-aluemainen-kayttotarkoitusalue" %}
Asemakaavan käyttötarkoitusalueiden ```geometria```-attribuutin kuvaamaan geometrian tulee olla aluemainen.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-ei-leikkaavat-kayttotarkoitusalueet" %}
Asemakaavan käyttötarkoitusalueet eivät saa leikata toisiaan.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-asemakaavan-kayttotarkoituspeite" %}
Asemakaavan, jonka ```elinkaaritila```-attribuutin arvo on kaavaehdotus tai myöhempi (Kaavaehdotus, Tarkistettu kaavaehdotus, Hyväksytty kaava, Oikaisukehotuksen alainen, Valituksen alainen, Osittain voimassa, Voimassa, Kumottu tai Kumoutunut), sisältämien käyttötarkoitusalueiden tulee peittää sen ```aluerajaus```-attribuutin ilmaisema kaavan alue siten, että kukin alueen sisäpiste sisältyy täsmälleen yhteen käyttötarkoitusalueeseen.
{% include common/clause_end.html %}

{% include common/question.html content="Alueen käyttötarkoituksen antaminen yhtenä kaavamääräyslajina tekee laatusäännöistä monimutkaisia, kun käyttötarkoitusalueita ei voida erotella tietyn yhden kaavamääräyslajin, vaan sen alakoodien avulla. Pitäisikö sittenkin antaa alueen käyttötarkoitus omana kaavamääräyslajinaan tai jopa palata ajatukseen kaavakohdelajin käyttämisestä käyttötarkoitusalueiden ilmoittamiseen?" %}

### Korkeusasemat

{% include common/clause_start.html type="req" id="prof-ak/vaat-maanpinnan-korkeusasema-konsistenssi" %}
[Maanpinnan korkeusasema](#maanpinnan-korkeusasema) -kaavamääräyksen arvon on vastattava kaavan [Pohjakartta](http://uri.suomi.fi/codelist/rytj/RY_LahtotietoaineistonLaji/code/11)-lajin [Lahtotietoaineiston](../../looginenmallin/dokumentaatio/#lahtotietoaineisto) topografisen aineiston maanpinnan korkeutta kaavakohteen sijannissa kuvaavaa arvoa.
{% include common/clause_end.html %}
