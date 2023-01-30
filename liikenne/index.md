---
layout: "default"
description: ""
id: "liikenne"
status: "Ehdotus"
---
# Kaavamääräyslajit - liikenne
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/08>

{% include common/question.html content="Kevyen liikenteen/pyöräily/jalankulku väyliä ei ole kuvattu asemakaavan kaavamääräyksinä. Alueen käyttötarkoituksessa on kyllä jalankululle ja pyöräilylle varattu alue. Miten ilmaistaan yhdistetty jalankulku ja pyöräilyväylä?" %}

1. 
{:toc}

## Ajoneuvoliittymän kielto
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0802>

{% include common/clause_start.html type="req" id="prof-ak/vaat-ajoneuvoliittyma-kielto-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka kohdalle ei saa rakentaa ajoneuvoliittymää. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-ajoneuvoliittyma-kielto-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}