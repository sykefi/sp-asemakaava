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
### Pysäköinnin määrä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/code/pysakoinninMaara>

Ryhmittelyotsikko, vain {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar" title="alakoodeja" %} käytetään.

Niin moottoajoneuvoille kuin polkupyörille varattujen pysäköintipaikkojen määrä voidaan ilmaista usealla tavalla.

Ilmaistaessa pysäköintipaikkojen kokonaismäärää, käytetään joko Kaavamääräys-koodia [Polkupyöräpysäköinnin määrä](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/polkupyoraPysakoinninMaara) tai [Autopaikkojen määrä](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/autopaikkojenMaara).

Ilmaistaessa pysäköintipaikkojen lukumäärää per asunto, käytetään joko Kaavamääräys-koodia [Polkupyöräpysäköinnin määrä per asunto](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/polkupyoraPysakoinninMaaraPerAsunto) tai [Autopaikkojen määrä per asunto](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/autopaikkojenMaaraPerAsunto).

Ilmaistaessa pysäköintipaikkojen lukumäärää per kerrosneliömetri, käytetään Kaavamääräys-koodia [Polkupyöräpysäköinnin määrä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/polkupyoraPysakoinninMaaraPerKerrosneliometri). tai [Autopaikkojen määrä per kerrosneliömetri](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarays/polkupyoraPysakoinninMaaraPerKerrosneliometri). Lisätiedon [Käyttötarkoituskohdistus](http://uri.suomi.fi/codelist/rytj/RY_Kaavamaarayksen_Lisatieto/kayttotarkoituskohdistus) ja sen ```arvo```-attribuutin avulla täsmennetään, minkä käyttötarkoituksen mukaiseen kerrosalaan pysäköinnin määrää verrataan.

{% include common/tip.html content="Mikäli halutaan antaa pysyköintipaikojen lukumäärät erikseen eri käyttötarkoituksille, voidaan kaavakohteella käyttää useampaa kaavamääräyksen ja sen lisätiedon yhdistelmää yllä kuvatulla tavalla kutakin käyttötarkoitusta kohden." %}

{% include common/clause_start.html type="req" id="prof-ak/vaat-polkupyorapaikkojen-maara-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#numeerinenarvovali" title="NumeerinenArvovali" %} joka kertoo vaaditun pysäköintipaikkojen minimimäärän, maksimimäärän tai molemmat sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvovälin minimi- ja maksimiarvojen on toteutettava {% include common/moduleLink.html moduleId="kaavatiedot" path="looginenmalli/dokumentaatio/#real" title="Real" %}-rajapinta. Yksikköä ei kirjata. Muun tyyppiset arvot eivät ole sallittuja.
{% include common/clause_end.html %}