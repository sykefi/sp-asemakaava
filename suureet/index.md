---
layout: "default"
description: ""
id: "suureet"
status: "Ehdotus"
---

# Kaavamääräykset - suureet
{:.no_toc}

Suure-tyyppisillä kaavamääräyksillä tarkoitetaan tässä [Kaavamääräys](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/)-koodiston koodeja, jotka sisältyvät määrityshierarkiaan ```Suure```.

{% include common/clause_start.html type="req" id="prof-yk/vaat-arvot" %}
Tyypiltään suuremaisille kaavamääräyksille on ```arvo```-attribuutin arvona annettava **täsmälleen yksi** {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %}.
{% include common/clause_end.html %}

Poikkeuksena ovat [Nimistö]((http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/nimisto))-luokkaan kuuluvat kaavamääräyskoodit, joiden arvon tulee olla tyyppiä {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#tekstiarvo" title="TekstiArvo" %}

## Rakentamisen tapa

### Kattokaltevuus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/kattokaltevuus>

{% include common/clause_start.html type="req" id="prof-ak/vaat-kattokaltevuus-arvot" %}
```arvo```-attribuutin arvoja saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} joka kertoo rakennusten katon sallitun kaltevuuden asteina (```deg```) sen kaavakohteen alueella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-kattokaltevuus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

### Rakennuksen harjan suunta
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/rakennuksenHarjanSuunta>

{% include common/clause_start.html type="req" id="prof-ak/vaat-harjasuunta-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} jotka kertovat rakennusten katon harjan sallitun kompassisuunnan asteina (```deg```) sen kaavakohteen alueella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-harjasuunta-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

### Ääneneristävyys
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0508>

{% include common/clause_start.html type="req" id="prof-ak/vaat-aaneneristavyys-arvot" %}
```arvo```-attribuutin mahdolliset arvot ovat seuraavat:
* Yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} joka kuvaa rakennuksen ulkoseinien sekä ikkunoiden ja muiden rakenteiden vähimmäisääneneristävyyden liikennemelua vastaan desibeleinä (```db```). Numeerisen arvon on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta.
* Nolla tai useampi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#geometriaarvo" title="GeometriaArvo" %} joka on päällekkäin sen kaavakohteen geometrian osan kanssa, jonka puoleisia sivuja kaavamääräys koskee.
{% include common/clause_end.html %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-aaneneristavyys-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}


### Vihertehokkuus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/vihertehokkuus>

{% include common/clause_start.html type="req" id="prof-ak/vaat-vihertehokuus-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä nolla tai yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvo" title="NumeerinenArvo" %} joka kertoo kaavakohteen alueen tonttien viherkertoimen vähimmäisarvon. Numeerisen arvon on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Muun tyyppiset arvot eivät ole sallittuja.

{% include common/clause_start.html type="req" id="prof-ak/vaat-vihertehokuus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include common/clause_end.html %}

## Liikenteen suureet
### Autopaikkojen määrä
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

### Polkupyöräpysäköinnin määrä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/polkupyoraPysakoinninMaara>

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