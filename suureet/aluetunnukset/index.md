---
layout: "default"
description: ""
id: "aluetunnukset"
status: "Ehdotus"
---
# Kaavamääräyslajit - Aluetunnukset
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/aluetunnukset>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

{% include common/clause_start.html type="req" id="prof-ak/suureet-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-aluetunnukset-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %}.  Numeerisen arvon on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#integer" title="Integer" %}-rajapinta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-korttelin-numero-kohdennus" %}
[Korttelin numero](<http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/korttelinNumero>) kohdennetaan
 kaavakohteeseen, johon liittyy alueen käyttötarkoitusta kuvaava [kaavamääräys](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays)-koodi.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-korttelin-numero-kohdennus" %}
[Tontin numero](<http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/tontinNumero>) kohdennetaan kaavakohteelle, johon liittyy kaavamääräys [tontti](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji/code/tontti).
{% include common/clause_end.html %}