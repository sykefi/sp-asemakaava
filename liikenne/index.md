---
layout: "default"
description: ""
id: "liikenne"
status: "Ehdotus"
---
# Kaavamääräyslajit - liikenne
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/08>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

{% include common/question.html content="Kevyen liikenteen/pyöräily/jalankulku väyliä ei ole kuvattu asemakaavan kaavamääräyksinä. Alueen käyttötarkoituksessa on kyllä jalankululle ja pyöräilylle varattu alue. Miten ilmaistaan yhdistetty jalankulku ja pyöräilyväylä?" %}

{% include common/question.html content="AK-kaavamääräyksissä ei ole raitiotie/pikaraitiotie/metroväyliä erikseen, vain yleinen rautatieliikenteen alue. Pitäiskö olla? Entä julkisen liikenteen pysäkit ja metron sisäänkäynti?" %}

1. 
{:toc}

## Ajoneuvoliittymä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0801>

{% include common/clause_start.html type="req" id="prof-ak/vaat-ajoneuvoliittyma-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, joka kuvaa ajoneuvoliittymän sijaintia alueen rajalla. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-ajoneuvoliittyma-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Ajoneuvoliittymän kielto
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0802>

{% include common/clause_start.html type="req" id="prof-ak/vaat-ajoneuvoliittyma-kielto-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka kohdalle ei saa rakentaa ajoneuvoliittymää. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-ajoneuvoliittyma-kielto-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Autopaikkojen määrä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0803>

Moottoajoneuvoille varattujen pysäköintipaikkojen lukumäärä voidaan ilmaista joko kaavakohteen alueelle toteutettavien paikkojen kokonaismääränä, lukumääränä per asunto tai lukumääränä per rakennusten kerrosneliömetri. Viimeksi mainitussa tapauksessa voidaan lukumäärä tarkentaa lisäksi koskemaan ainoastaan annettuun käyttötarkoitukseen toteutettavia kerrosneliömetrejä.

{% include common/clause_start.html type="req" id="prof-ak/vaat-autopaikkojen-maara-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} joka kertoo vaaditun pysäköintipaikkojen minimimäärän, maksimimäärän tai molemmat sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#integer" title="Integer" %}-rajapinta. Yksikköä ei käytetä. Muun tyyppiset arvot eivät ole sallittuja.

Mikäli arvoa ei anneta, tulee lukumäärä ilmaista ```lisätieto```-attribuutin avulla.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-autopaikkojen-maara-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatieto" %} jonka laji on joko [Lukumäärä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/12), tai [Lukumäärä per asunto](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/13).

Mikäli lisätiedon laji on [Lukumäärä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/12), tulee sillä olla vähintään yksi ja enintään kaksi arvoa:
*  Yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} joka kertoo pysäköintipaikkojen minimimäärän, maksimimäärän tai molemmat jokaista kaavakohteen alueella sijaitsevan rakennuksen kerrosneliömetriä kohden. Numeerisen arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Yksikköä ei käytetä.
* Nolla tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} joka viittaa [KaavamääraysLaji](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) koodien [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) tai [Alueen osan käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/02) johonkin alakoodiin.

Mikäli lisätiedon laji on [Lukumäärä per asunto](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/13), tulee sillä olla täsmälleen yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} joka kertoo pysäköintipaikkojen minimimäärän, maksimimäärän tai molemmat jokaista kaavakohteen alueella sijaitsevan rakennuksen asuntoa kohden. Yksikköä ei käytetä.
{% include common/clause_end.html %}

{% include common/tip.html content="Mikäli halutaan antaa pysyköintipaikojen lukumäärät erikseen eri käyttötarkoituksiin, voidaan käyttää useampaa [Lukumäärä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/12)-lajin lisätietoa, joissa kussakin annetaan lukumäärä tiettyjä käyttötarkoituksia kohden." %}

## Polkupyöräpysäköinnin määrä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0804>

Polkupyöräpysäköintipaikkojen lukumäärä voidaan ilmaista joko kaavakohteen alueelle toteutettavien paikkojen kokonaismääränä, lukumääränä per asunto tai lukumääränä per rakennusten kerrosneliömetri. Viimeksi mainitussa tapauksessa voidaan lukumäärä tarkentaa lisäksi koskemaan ainoastaan annettuun käyttötarkoitukseen toteutettavia kerrosneliömetrejä.

{% include common/clause_start.html type="req" id="prof-ak/vaat-polkupyorapaikkojen-maara-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} joka kertoo vaaditun pysäköintipaikkojen  minimimäärän, maksimimäärän tai molemmat sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#integer" title="Integer" %}-rajapinta. Yksikköä ei käytetä. Muun tyyppiset arvot eivät ole sallittuja.

Mikäli arvoa ei anneta, tulee lukumäärä ilmaista ```lisätieto```-attribuutin avulla.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-polkupyorapaikkojen-maara-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#lisatieto" title="Lisatieto" %} jonka laji on joko [Lukumäärä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/12), tai [Lukumäärä per asunto](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/13).

Mikäli lisätiedon laji on [Lukumäärä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/12), tulee sillä olla vähintään yksi ja enintään kaksi arvoa:
*  Yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} joka kertoo pysäköintipaikkojen minimimäärän, maksimimäärän tai molemmat jokaista kaavakohteen alueella sijaitsevan rakennuksen kerrosneliömetriä kohden. Numeerisen arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Yksikköä ei käytetä.
* Nolla tai Yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#koodiarvo" title="KoodiArvo" %} joka viittaa [KaavamääraysLaji](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) koodien [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) tai [Alueen osan käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/02) johonkin alakoodiin.

Mikäli lisätiedon laji on [Lukumäärä per asunto](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/13), tulee sillä olla täsmälleen yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} joka kertoo pysäköintipaikkojen minimimäärän, maksimimäärän tai molemmat jokaista kaavakohteen alueella sijaitsevan rakennuksen asuntoa kohden. Numeerisen arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Yksikköä ei käytetä.

Muun tyyppiset lisätietojen arvot eivät ole sallittuja.

{% include common/clause_end.html %}

{% include common/tip.html content="Mikäli halutaan antaa pysyköintipaikojen lukumäärät erikseen eri käyttötarkoituksiin, voidaan käyttää useampaa [Lukumäärä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/12)-lajin lisätietoa, joissa kussakin annetaan lukumäärä tiettyjä käyttötarkoituksia kohden." %}