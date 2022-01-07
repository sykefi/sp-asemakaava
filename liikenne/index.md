---
layout: "default"
description: ""
id: "liikenne"
status: "Ehdotus"
---
# Kaavamääräyslajit - liikenne
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/08>

Ryhmittelyotsikko, vain [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.

{% include common/question.html content="Kevyen liikenteen/pyöräily/jalankulku väyliä ei ole kuvattu asemakaavan kaavamääräyksinä. Alueen käyttötarkoituksessa on kyllä jalankululle ja pyöräilylle varattu alue. Miten ilmaistaan yhdistetty jalankulku ja pyöräilyväylä?" %}

{% include common/question.html content="AK-kaavamääräyksissä ei ole raitiotie/pikaraitiotie/metroväyliä erikseen, vain yleinen rautatieliikenteen alue. Pitäiskö olla? Entä julkisen liikenteen pysäkit ja metron sisäänkäynti?" %}

1. 
{:toc}

## Ajoneuvoliittymä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0801>

{% include common/clause_start.html type="req" id="prof-ak/vaat-ajoneuvoliittyma-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi tai useampi [GeometriaArvo](../../looginenmalli/dokumentaatio/#geometriaarvo), joka on päällekkäin sen kaavakohteen geometrian osan kanssa, joka kuvaa ajoneuvoliittymän sijaintia alueen rajalla. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-ajoneuvoliittyma-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Ajoneuvoliittymän kielto
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0802>

{% include common/clause_start.html type="req" id="prof-ak/vaat-ajoneuvoliittyma-kielto-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi tai useampi [GeometriaArvo](../../looginenmalli/dokumentaatio/#geometriaarvo), joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka kohdalle ei saa rakentaa ajoneuvoliittymää. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-ajoneuvoliittyma-kielto-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Autopaikkojen määrä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0803>

Moottoajoneuvoille varattujen pysäköintipaikkojen lukumäärä voidaan ilmaista joko kaavakohteen alueelle toteutettavien paikkojen kokonaismääränä, lukumääränä per asunto tai lukumääränä per rakennusten kerrosneliömetri. Viimeksi mainitussa tapauksessa voidaan lukumäärä tarkentaa lisäksi koskemaan ainoastaan annettuun käyttötarkoitukseen toteutettavia kerrosneliömetrejä.

{% include common/clause_start.html type="req" id="prof-ak/vaat-autopaikkojen-maara-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali) joka kertoo vaaditun pysäköintipaikkojen minimimäärän, maksimimäärän tai molemmat sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvovälin minimi- ja maksimiarvojen on toteutettava [Integer](../../looginenmalli/dokumentaatio/#integer)-rajapinta. Yksikköä ei käytetä. Muun tyyppiset arvot eivät ole sallittuja.

Mikäli arvoa ei anneta, tulee lukumäärä ilmaista ```lisätieto```-attribuutin avulla.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-autopaikkojen-maara-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), jonka laji on joko [Lukumäärä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/12), tai [Lukumäärä per asunto](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/13).

Mikäli lisätiedon laji on [Lukumäärä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/12), tulee sillä olla vähintään yksi ja enintään kaksi arvoa:
*  Yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), joka kertoo pysäköintipaikkojen minimimäärän, maksimimäärän tai molemmat jokaista kaavakohteen alueella sijaitsevan rakennuksen kerrosneliömetriä kohden. Numeerisen arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta. Yksikköä ei käytetä.
* Nolla tai yksi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), joka viittaa [KaavamääraysLaji](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) koodien [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) tai [Alueen osan käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/02) johonkin alakoodiin.

Mikäli lisätiedon laji on [Lukumäärä per asunto](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/13), tulee sillä olla täsmälleen yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), joka kertoo pysäköintipaikkojen minimimäärän, maksimimäärän tai molemmat jokaista kaavakohteen alueella sijaitsevan rakennuksen asuntoa kohden. Yksikköä ei käytetä.
{% include common/clause_end.html %}

{% include common/tip.html content="Mikäli halutaan antaa pysyköintipaikojen lukumäärät erikseen eri käyttötarkoituksiin, voidaan käyttää useampaa [Lukumäärä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/12)-lajin lisätietoa, joissa kussakin annetaan lukumäärä tiettyjä käyttötarkoituksia kohden." %}

## Polkupyöräpysäköinnin määrä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0804>

Polkupyöräpysäköintipaikkojen lukumäärä voidaan ilmaista joko kaavakohteen alueelle toteutettavien paikkojen kokonaismääränä, lukumääränä per asunto tai lukumääränä per rakennusten kerrosneliömetri. Viimeksi mainitussa tapauksessa voidaan lukumäärä tarkentaa lisäksi koskemaan ainoastaan annettuun käyttötarkoitukseen toteutettavia kerrosneliömetrejä.

{% include common/clause_start.html type="req" id="prof-ak/vaat-polkupyorapaikkojen-maara-arvot" %}
```arvo```-attribuutin arvona saa esiintyä nolla yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), joka kertoo vaaditun pysäköintipaikkojen  minimimäärän, maksimimäärän tai molemmat sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvovälin minimi- ja maksimiarvojen on toteutettava [Integer](../../looginenmalli/dokumentaatio/#integer)-rajapinta. Yksikköä ei käytetä. Muun tyyppiset arvot eivät ole sallittuja.

Mikäli arvoa ei anneta, tulee lukumäärä ilmaista ```lisätieto```-attribuutin avulla.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-polkupyorapaikkojen-maara-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), jonka laji on joko [Lukumäärä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/12), tai [Lukumäärä per asunto](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/13).

Mikäli lisätiedon laji on [Lukumäärä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/12), tulee sillä olla vähintään yksi ja enintään kaksi arvoa:
*  Yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), joka kertoo pysäköintipaikkojen minimimäärän, maksimimäärän tai molemmat jokaista kaavakohteen alueella sijaitsevan rakennuksen kerrosneliömetriä kohden. Numeerisen arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta. Yksikköä ei käytetä.
* Nolla tai Yksi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), joka viittaa [KaavamääraysLaji](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) koodien [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) tai [Alueen osan käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/02) johonkin alakoodiin.

Mikäli lisätiedon laji on [Lukumäärä per asunto](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/13), tulee sillä olla täsmälleen yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), joka kertoo pysäköintipaikkojen minimimäärän, maksimimäärän tai molemmat jokaista kaavakohteen alueella sijaitsevan rakennuksen asuntoa kohden. Numeerisen arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta. Yksikköä ei käytetä.

Muun tyyppiset lisätietojen arvot eivät ole sallittuja.

{% include common/clause_end.html %}

{% include common/tip.html content="Mikäli halutaan antaa pysyköintipaikojen lukumäärät erikseen eri käyttötarkoituksiin, voidaan käyttää useampaa [Lukumäärä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/12)-lajin lisätietoa, joissa kussakin annetaan lukumäärä tiettyjä käyttötarkoituksia kohden." %}

## Muu liikenteeseen liityvä määräys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0805>

{% include common/clause_start.html type="req" id="prof-ak/vaat-muu-liikenne-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka kuvaa kaavamääräyksen. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-muu-liikenne-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}
