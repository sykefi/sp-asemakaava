---
layout: "default"
title: "Kaavatietomallin soveltamisprofiili - asemakaava"
description: ""
id: "ktm-asemakaava"
status: "Ehdotus"
---
# Kaavatietomallin soveltamisprofiili asemakaava-aineistoille
{:.no_toc}

## Johdanto

Tämän dokumentin vaatimukset ja suositukset muodostavat Kaavatietomallin loogisen tietomallin soveltamisprofiilin asemakaava-aineistoille. Soveltamisprofiili kuvaa ne rajoitukset ja lisävaatimukset, joita tulee noudattaa Kaavatietomallin [UML-kielisen kuvauksen](../../looginenmalli/uml/) ja sen [sanallisen dokumentaation](../../looginenmalli/dokumentaatio/) soveltamisessa asemakaavojen tietoaineistojen kuvaamiseen.

Tämän muodollisen dokumentin tietoja täydentää [Asemakaavan kaavamääräysopas]() **TODO:LINKKI**, joka sisältää käytännön esimerkkejä Kaavatietomallin soveltamisesta asemakaavoituksen kaavoitusratkaisuihin.

{% include common/clause_start.html type="req" id="prof-ak/vaat-asemakaava-aineisto-maar" %}
Kaavatietomallin mukainen asemakaava-aineisto koostuu [Kaava](../../looginenmalli/dokumentaatio/#kaava)-luokan instansseista, joiden ```laji```-attribuutin arvo on jokin [Kaavalajit]()-koodiston koodin [Asemakaava](http://uri.suomi.fi/codelist/rytj/RY_Kaavalaji/code/3) [alakoodeista](../../looginenmalli/elinkaarisaannot.html#elinkaari-vaat-alakoodi-maar), sekä näihin instansseihin Kaavatietomallin mukaisesti liittyvistä muiden luokkien instansseista.
{% include common/clause_end.html %}

## Sisällys

* [Koodistot](./koodistot.html)
* Kaavamääräyslajien arvot ja lisätiedot
   * [Käyttötarkoitukset](./kaavamaarayslajit/kayttotarkoitukset.html)
   * [Rakentamisen määrä](./kaavamaarayslajit/rakentamisen-maara.html)
   * [Rakennusten sijoittaminen](./kaavamaarayslajit/rakennusten-sijoitus.html)
   * [Rakentamistapa](./kaavamaarayslajit/rakentamistapa.html)
   * [Korkeusasemat](./kaavamaarayslajit/korkeusasema.html)
   * [Ulkoalueet](./kaavamaarayslajit/ulkoalueet.html)
   * [Liikenne](./kaavamaarayslajit/liikenne.html)
   * [Ympäristöarvojen vaaliminen](./kaavamaarayslajit/ymparistoarvojen-vaaliminen.html)
   * [Tonttijako](./kaavamaarayslajit/tonttijako.html)
   * [Yhdyskuntatekninen huolto](./kaavamaarayslajit/yhdyskuntatekninen-huolto.html)
   * [Ympäristön ja terveyden suojelu](./kaavamaarayslajit/ympariston-ja-terveyden-suojelu.html)
   * [Nimistö](./kaavamaarayslajit/nimistö.html)
   * [Yleismääräykset](./kaavamaarayslajit/yleismaaraykset.html)
* [Laatusäännöt](./laatusaannot.html)