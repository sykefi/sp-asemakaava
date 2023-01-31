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

## Melueste
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/melueste>

{% include common/clause_start.html type="req" id="prof-ak/vaat-melueste-arvot" %}
Melueste-koodin tai sen alakoodien omaavien Kaavamääräysten ```arvo```-attribuutin arvoina saa esiintyä nolla tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} joka kuvaa aidan vähimmäisääneneristävyyden liikennemelua vastaan desibeleinä (```db```). Numeerisen arvon on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}
