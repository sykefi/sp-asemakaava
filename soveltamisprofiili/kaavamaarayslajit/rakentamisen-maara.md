---
layout: "default"
title: "Kaavatietomallin soveltamisprofiili - asemakaava - rakentamisen määrä"
description: ""
id: "rakentamisen-maara"
status: "Ehdotus"
---
# Kaavamääräyslajit - rakentamisen määrä
{:.no_toc}

**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji/code/03>

Ryhmittelyotsikko, vain [alakoodeja](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar) käytetään.

1. 
{:toc}

## Sallittu kerrosala
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0301>

{% include clause_start.html type="req" id="prof-ak/vaat-sallittu-kerrosala-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) tai yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), joka kertoo sallitun rakentamiseen kokonaismäärän kerrosneliömetreinä (```k-m2```) sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-ak/vaat-sallittu-kerrosala-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), jonka laji on [Käyttötarkoituksen osuus kerrosalasta](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/01), jolla on täsmälleen kaksi arvoa:
*  Yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) tai yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), jotka kertovat sallitun tiettyyn käyttötarkoitukseen kohdistettavan kerroalan määrän koko sallitusta kerrosalasta joko kerrosneliömetreinä (```k-m2```) tai prosentteina (```%```). Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta.
* Yksi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), joka viittaa KaavamääraysLaji-koodiston koodien [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) tai [Alueen osan käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/02) johonkin alakoodiin.
{% include clause_end.html %}

Mikäli sallittua rakentamisen määrää ei ole jaoteltu käyttötarkoituksittain, ei lisätietoja käytetä.

## Sallittu rakennustilavuus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0302>

{% include clause_start.html type="req" id="prof-ak/vaat-sallittu-rakennustilavuus-arvot" %}
```arvo```-attribuutin arvoina saa esiintyä yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) tai yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), jotka kertovat sallitun rakentamisen kokonaismäärän kuutiometreinä (```m3```) sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-ak/vaat-sallittu-rakennustilavuus-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), jonka laji on [Käyttötarkoituksen osuus kerrosalasta](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/01), jolla on täsmälleen kaksi arvoa:
*  Yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) tai yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), jotka kertovat sallitun tiettyyn käyttötarkoitukseen kohdistettavan rakennustilavuuden määrän koko sallitusta rakennustilavuudesta joko kuutiometreinä (```k-m3```) tai prosentteina (```%```). Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta.
* Yksi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), joka viittaa [KaavamääraysLaji](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) koodien [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) tai [Alueen osan käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/02) johonkin alakoodiin.
{% include clause_end.html %}

Mikäli sallittua rakentamisen määrää ei ole jaoteltu käyttötarkoituksittain, ei lisätietoja käytetä.

{% include question.html content="Tuleeko käyttää termiä 'kerroskuutiometri' vai riittääkö 'kuutiometri'? Miten rakennustilavuus lasketaan (vrt.kerrosneliömetrit)?" %}

{% include question.html content="Onko järkevää ilmaista sallittu rakennustilavuus eri kaavamääräyslajina kuin sallittu kerrosala. Nykyisellään rakenne on identtinen, vain yksiköt eroavat" %}

## Tehokkuusluku
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0303>

{% include clause_start.html type="req" id="prof-ak/vaat-tehokkuusluku-arvot" %}
```arvo```-attribuutin arvona saa esiintyä joko yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) tai yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), jotka kertovat rakennustehokkuden, eli alueen rakennusten yhteenlasketun kerrosalan suhteessa alueen pinta-alaan, sen kaavakohteen aluella, johon kaavamääräys on liitetty. Ilmaistaan tehokkuuslukuna ```e```, yksikkönä ```k-m2/m2```. Muun tyyppiset arvot eivät ole sallittuja. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-ak/vaat-vaat-tehokkuusluku-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

{% include question.html content="Pitäisikö määräyksen nimi olla Rakennustehokkuus, tehokkuusluku on tapa ilmaista käsite numerona?" %}

## Maanpäällinen kerrosluku
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0304>

{% include clause_start.html type="req" id="prof-ak/vaat-maanpaallinen-kerrosluku-arvot" %}
```arvo```-attribuutin arvona saa esiintyä joko yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) tai yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), jotka kertovat rakennusten maanpäällisten kerrosten sallitun lukumäärän sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Integer](../../looginenmalli/dokumentaatio/#integer)-rajapinta. Yksikköjä ei käytetä. Muun tyyppiset arvot eivät ole sallittuja. 
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-ak/vaat-maanpaallinen-kerrosluku-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Maanalainen kerrosluku
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0305>

{% include clause_start.html type="req" id="prof-ak/vaat-maanalainen-kerrosluku-arvot" %}
```arvo```-attribuutin arvona saa esiintyä joko yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) tai yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), jotka kertovat rakennusten maanalaisten kerrosten sallitun lukumäärän sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Integer](../../looginenmalli/dokumentaatio/#integer)-rajapinta. Yksikköjä ei käytetä. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-ak/vaat-maanalainen-kerrosluku-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}


## Kellarin sallittu kerrosalaosuus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0306>

{% include clause_start.html type="req" id="prof-ak/vaat-kellarin-sallittu-kerrosalaosuus-arvot" %}
```arvo```-attribuutin arvona saa esiintyä joko yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) tai yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), jotka kertovat kuinka suuren osan kunkin rakennuksen suurimman kerroksen alasta saa kellarikerroksessa käyttää kerrosalaan luettavaksi tilaksi sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta. Ilmaistaan prosentteina (```%```). Muun tyyppiset arvot eivät ole sallittuja. 
{% include clause_end.html %}

{% include tip.html content="Murtolukuna ilmaistun osuuden voi ilmaista likimääräisesti myös arvovälinä, esim. ```1/3``` olisi ```33-34%```" %}

{% include clause_start.html type="req" id="prof-ak/vaat-kellarin-sallittu-kerrosalaosuus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Ullakon sallittu kerrosalaosuus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0307>

{% include clause_start.html type="req" id="prof-ak/vaat-ullakon-sallittu-kerrosalaosuus-arvot" %}
```arvo```-attribuutin arvona saa esiintyä joko yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) tai yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), jotka kertovat kuinka suuren osan kunkin rakennuksen suurimman kerroksen alasta saa ullakkokerroksessa käyttää kerrosalaan luettavaksi tilaksi sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta. Ilmaistaan prosentteina (```%```). Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include tip.html content="Murtolukuna ilmaistun osuuden voi ilmaista likimääräisesti myös arvovälinä, esim. ```1/3``` olisi ```33-34%```" %}

{% include clause_start.html type="req" id="prof-ak/vaat-ullakon-sallittu-kerrosalaosuus-lisatiedot" %}
```lisatieto```-attribuutilla ei saa olla arvoja.
{% include clause_end.html %}

## Rakennuspaikkojen määrä
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0308>

{% include clause_start.html type="req" id="prof-ak/vaat-rakennuspaikkojen-maara-arvot" %}
```arvo```-attribuutin arvona saa esiintyä yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) joka kertoo sallitun rakennuspaikkojen enimmäismäärän sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Integer](../../looginenmalli/dokumentaatio/#integer)-rajapinta. Yksikköä ei käytetä. Muun tyyppiset arvot eivät ole sallittuja.
{% include clause_end.html %}

{% include clause_start.html type="req" id="prof-ak/vaat-rakennuspaikkojen-maara-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä nolla tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), jonka laji on [Käyttötarkoituskohdistus](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/02), jolla on täsmälleen yksi ```arvo``` lajia [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), joka viittaa johonkin [Rakennusluokitus 2018](http://uri.suomi.fi/codelist/jhs/rakennus_1_20180712)-koodiston koodiin. Muun tyyppiset arvot eivät ole sallittuja.

Mikäli vähintään yksi lisätieto on annettu, koskee rakennuspaikkojen lukumäärä vain lisätietojen avulla rajattuja rakennustyyppejä.
{% include clause_end.html %}

{% include note.html content="Käytetään tavallisesti vain ranta-asemakaavoissa" %}

## Lisärakennusoikeus
**Koodi**: <http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/0309>

{% include clause_start.html type="req" id="prof-ak/vaat-lisarakennusoikeus-arvot" %}
```arvo```-attribuutin mahdolliset arvot ovat seuraavat:
* Yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) tai yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), joka kertoo sallitun lisärakentamisen kokonaismäärän joko kerrosneliömetreinä (```k-m2```) tai kuutiometreinä (```m3```) sen kaavakohteen aluella, johon kaavamääräys on liitetty. Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta.
* Nolla tai useampi [TekstiArvo](../../looginenmalli/dokumentaatio/#tekstiarvo) (yksi kullakin kielellä), joka täydentää kaavamääräystietoa.
{% include clause_end.html %}


{% include clause_start.html type="req" id="prof-ak/vaat-lisarakennusoikeus-lisatiedot" %}
```lisatieto```-attribuutin arvoina saa esiintyä yksi tai useampi [Lisatieto](../../looginenmalli/dokumentaatio/#lisatieto), jonka laji on [Käyttötarkoituksen osuus kerrosalasta](http://uri.suomi.fi/codelist/rytj/RY_Lisatiedonlaji_AK/code/01), jolla on täsmälleen kaksi arvoa:
*  Yksi [NumeerinenArvo](../../looginenmalli/dokumentaatio/#numeerinenarvo) tai yksi [NumeerinenArvovali](../../looginenmalli/dokumentaatio/#numeerinenarvovali), jotka kertovat sallitun tiettyyn käyttötarkoitukseen kohdistettavan kerroalan määrän koko sallitusta kerrosalasta joko kerrosneliömetreinä (```k-m2```), kuutioina (```m3```) tai prosentteina (```%```). Numeerisen arvon tai arvovälin minimi- ja maksimiarvojen on toteutettava [Real](../../looginenmalli/dokumentaatio/#real)-rajapinta.
* Yksi [KoodiArvo](../../looginenmalli/dokumentaatio/#koodiarvo), joka viittaa [KaavamääraysLaji](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) koodien [Alueen käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/01) tai [Alueen osan käyttötarkoitus](http://uri.suomi.fi/codelist/rytj/RY_KaavamaaraysLaji_AK/code/02) johonkin alakoodiin.
{% include clause_end.html %}

{% include question.html content="Miten lisärakennusoikeus eroaa käyttötarkoituskohtaisesti sallitusta kerrosalasta tai rakennustilavuudesta? Missä tapauksissa lisärakennusoikeutta käytettäisiin? Nykyisellään rakenne on lähes identtinen" %}

