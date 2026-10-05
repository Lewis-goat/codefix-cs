---
title: Chyba 2 u Jury v zimě – studený stroj, ne rozbitý díl
description: Chyba 2 u kávovarů Jura často neznamená poruchu. Pod 10 °C se topení blokuje. Protokol ohřevu a kdy jde doopravdy o NTC čidlo či pojistku.
---

Chyba 2 je nejčastějším kódem na automatických kávovarech Jura – řady E, ENA, S, J, Z i GIGA sdílejí stejné číslování – a má dvě zcela odlišné podoby. Buď se přerušil obvod teplotního snímače kávového termobloku, nebo je stroj jednoduše příliš studený na to, aby topil. V zimě na tu druhou možnost narazí překvapivě mnoho majitelů, kteří neudělali nic špatně, a přitom jde o příčinu, na kterou chybová hláška sama nikdy nenaznačí. Kompletní referenční výklad najdete na [stránce Jura Error 2](https://cs.codefixcoffee.com/jura/automatic-machines/error-2/); tento článek popisuje tu studenou polovinu příběhu.

## Co vám stroj ve skutečnosti říká

Chyby 1 až 5 u Jury se týkají topných termobloků a jejich čidel. Když elektronika zaznamená teplotu, kterou nedokáže sladit s topením, jež nařídila, topení vypne a odmítá to zkusit znovu – jde o ochranné uzamčení, nikoli nutně o poruchu. Pod zhruba 10 °C se studený termoblok nachází hluboko mimo rozsah, který deska očekává, a stroj to vyhodnotí naprosto stejně jako vadné čidlo. Nic není rozbité. Stroj je studený.

Scénář je klasický: stroj dovezený v zimě v nevytápěné dodávce, Jura ve studené kuchyni, zimní zahradě, garážové kanceláři či na chalupě, anebo čerstvě vybalený a rovnou spuštěný. Vzor je vždy tentýž – dříve fungoval bez problémů, Error 2 se objeví při prvním startu a žádné tlačítko ho nesmaže.

Kávovary obecně nerady startují za studena. U automatů Philips a Saeco existuje obdoba – [chyba 11 nebo 19](https://cs.codefixcoffee.com/philips-saeco/espresso-machines/error-11-or-19/) znamená, že se stroj po studené dopravě musí přizpůsobit pokojové teplotě, jak popisuje i [podpora Philips](https://www.philips.com/).

## Protokol ohřevu

Absolvujte ho dřív, než usoudíte, že se něco rozbilo. Nic nestojí a u studeného stroje jde vždy o první pokus.

1. Přemístěte stroj do vytopené místnosti a dejte mu čas – několik hodin, než dosáhne skutečné pokojové teploty, ne jen než zvenku přestane působit chladně. Těleso, které se jeví v pořádku, může uvnitř stále skrývat termoblok hluboko pod 10 °C.

2. Chcete-li proces zrychlit, foukejte fémem na nejnižším stupni zhruba pět minut do dutiny vodní nádržky, nebo nádržku naplňte teplou – nikoli horkou – vodou z kohoutku.

3. Stroj restartujte.

4. Zmizí-li Error 2 po ohřevu, nic se nepokazilo. Udržujte stroj v teple a kód se nevrátí.

Dbjte dvou varování. Teplá voda znamená teplá, ne horká – nádržka, ventily i těsnění jsou plastové. A nemiřte soustředěné teplo na tělo stroje ani na elektroniku; cílem je odstranit chlad z termobloku, ne uvařit kabeláž v jeho okolí.

## Kdy jde opravdu o NTC čidlo nebo pojistkové vodiče

Stál-li stroj hodiny v teplé místnosti a Error 2 se stále hlásí, nevinné vysvětlení padá a obvod snímače je přerušený. Uvnitř Jury to pak znamená jednu ze dvou zásad:

- NTC teplotní čidlo na kávovém termobloku selhalo, nebo jeho konektor ztratil kontakt. Sesterským kódem je [Jura Error 1](https://cs.codefixcoffee.com/jura/automatic-machines/error-1/), vlastní závada snímače kávového termobloku; obě poruchy sdílejí díly i příznaky.

- Dva pojistkové vodiče, které termoblok chrání, se přerušily – vyhoří po přehřátí, nebo prostě stářím. Přerušený pojistkový vodič se na multimetru jeví jako rozpojený.

Oprava se většinou vyplatí. Originální NTC čidlo Jura stojí přibližně €25 až €40 a sada pojistkových vodičů €15 až €30; technici je zpravidla mění společně, protože práce je stejná. Smysl dává i celý termoblok za €90 až €180, zvlášť u vyšších modelů. Byla-li vaše Jura celou dobu v teple, pak právě tohle – a ne počasí – je váš Error 2.

## Varovný signál po opravě

Jedna past si zaslouží vlastní odstavec. Pojistkový vodič, který jednou vyhořel, vyhoří znovu, drží-li napájecí deska topení trvale zapnuté. Selže-li nově osazený vodič během pár dnů, přestaňte vyměňovat pojistky – závada sídlí v napájecí desce. Deska typicky stojí €120 až €250 plus práce, což u staršího stroje vede k úvaze o opravě versus pořízení nového, ne k objednávce dílů.

## Bezpečnost a hranice vlastních sil

Otevřít Juru není jako otevřít konvici. Kryt drží pojistné šrouby Torx-Plus s oválnými hlavami a na termoblocích je síťové napětí. Nemáte-li odpovídající bit, multimetr a klid na práci s elektrickou instalací, patří tato fáze na servisní stůl. Protokol ohřevu je uživatelská půlka příběhu Error 2; snímač a pojistkové vodiče jsou půlka dílnenská.

Ekonomika zůstává přátelská v obou směrech. Ohřev nic nestojí a realistický účet za díly při opravě snímače a pojistkových vodičů se drží zhruba do €50. Zbytkem kódové sady značky – ventily, varné jednotky i topné kódy napříč modelovými řadami – se zabývá [přehled chybových kódů Jura](https://cs.codefixcoffee.com/jura/). A mají-li domácnost i další kávovary, systémy Miele CM a CVA používají schéma F-kódů indexované pod [Miele](https://cs.codefixcoffee.com/miele/).

### Zima v českých podmínkách

Typický český scénář? Kávovar přivezený v prosinci kurýrem, anebo stroj od listopadu zapomenutý na chalupě či v nevytopené zimní zahradě. Po dopravě mrazem nechte automat aspoň do druhého dne aklimatizovat při pokojové teplotě, než ho poprvé zapnete – totéž doporučuje v pokynech k prvnímu použití přímo [Jura](https://www.jura.com/). A necháváte-li stroj na chalupě přes zimu, před odjezdem vylijte vodu z nádržky, aby zmrzlá neroztrhala hadičky a nepoškodila čerpadlo.
