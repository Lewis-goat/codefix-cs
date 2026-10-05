---
title: Kódy ER u Sage/Breville: jak číst skrytou servisní tabulku
description: Espresso stroje Sage a Breville zobrazují kódy ER z tabulek, které výrobce nikdy nezveřejnil. Jak funguje číslování ER01–ER18 a proč se Oracle liší.
---

Ztuhne-li espresso stroj Breville a na panelu svítí ER05, význam vám manuál neřekne. Nejde o opomenutí: kódy chyb Breville pocházejí z interních servisních tabulek, podle nichž se stroje opravují a které se majitelům nedostávají do rukou. Tentýž hardware se v Británii prodává pod značkou **Sage** — přístroje jsou identické, liší se jen štítkem, a proto ER kód na Sage Barista Touch znamená totéž co na stroji Breville. [Sekce Breville / Sage](https://cs.codefixcoffee.com/breville/) pokrývá aktuální modely; tento článek vysvětluje, jak je číslování uspořádáno, aby vám i kód, který jste nikdy neviděli, něco prozradil. Údržbové pokyny k jednotlivým strojům najdete v oficiální podpoře [sageappliances.co.uk](https://www.sageappliances.co.uk).

## Proč je Breville nezveřejňuje

Uživatelský manuál řeší čištění a odvápnění, ne diagnostiku. Kompletní tabulky kódů žijí v servisním režimu každého stroje: v heslem chráněných obrazovkách určených technikům, s uloženými počítadly chyb a živými údaji čidel. Protože jde o opravářský nástroj a nikoli o funkci pro zákazníky, Breville kódy nikdy v žádném veřejném dokumentu nevydalo, a většina majitelů za celou dobu uvidí jediný kód — ten, kvůli kterému se stroj vypnul. Kontrast je ostrý: Miele významy svých kódů F tiskne přímo v návodech k obsluze, a proto mohou [stránky kódů Miele](https://cs.codefixcoffee.com/miele/) manuál citovat doslova.

## Tabulka Barista Touch: ER01 až ER18

Barista Touch (BES880) i Barista Touch Impress (BES881) sdílejí rodinu řídicích desek i tabulku kódů, a proto pracují s osmnácti položkami. Jakmile jednou pochopíte strukturu, čte se tabulka sama: kódy čidel přicházejí ve **čtveřicích**, na každé čidlo jedna, a střídají přerušení obvodu při startu, přerušení za provozu, zkrat při startu a zkrat za provozu.

- **ER01 až ER04** — teplotní čidlo topení ThermoJet ve všech čtyřech variantách přerušení a zkratu; [ER01](https://cs.codefixcoffee.com/breville/barista-touch-bes880/er01/) je položka pro přerušení obvodu při startu.
- **ER05 až ER08** — teplotní čidlo mléčné konvice, malá sonda u odkapávací misky, která během šlehání čte teplotu konvice. ER05, startovní přerušení, je nejčastěji hlášený kód Barista Touch a všechny čtyři položky řeší jediná oprava.
- **ER09 až ER12** — průtočné čidlo teploty vařicí vody, týž čtyřvariantní vzorec.
- **ER13 a ER14** — chyby počtů průtokoměru, při startu a za provozu: čerpadlo běželo, ale stroj nedokázal spočítat vodu, kterou jím protlačoval.
- **ER15** — komunikační porucha mezi vnitřními elektronickými moduly; často uvolněná plochá svazková lišta nebo vlhký konektor, nikoli nutně mrtvá deska.
- **ER16 a ER17** — mlýnek: motor se přehřál a ochranně vypnul, poté úlohu nedokončil ani v časovém limitu.
- **ER18** — ochrana E-fast, tedy elektrická nebo bezpečnostní závada, například únikový proud; je to kód, který umí shodit i proudový chránič v zásuvce.

## Rodina Oracle čísluje jinak

S Oraclem dostanete tutéž myšlenku v delším provedení. Oracle (BES980) a Oracle Touch (BES990) sdílejí seznam 32 položek, jen BES980 je zobrazuje jako „Error 1“ až „Error 32“, zatímco BES990 předřazuje předponu ER. Prvních šestnáct následuje logiku kvartet napříč čtyřmi čidly — parní kotel na 1 až 4, kávový kotel na 5 až 8 (kde [Error 8](https://cs.codefixcoffee.com/breville/oracle-bes980/error-8/) znamená zkrat čidla kávového kotle za provozu), ohřívaná varná jednotka na 9 až 12, parní páka na 13 až 16. Zbytek patří kotlům, které se nehřejí (17 až 19), hladině a doplňování parního kotle (20 a 21), průtokoměru (22 a 23), hladinovým sondám a přehřívání (24 až 27), komunikační poruše desky na 28, mlýnku na 29 a 30, tampovacímu motoru na 31 a úniku z parního kotle či selhání doplnění na 32.

Rodinu doplňují dvě menší tabulky. Oracle Jet (BES985) má vlastní zkrácenou řadu E1 až E19 a Dual Boiler (BES920) drží dvouciferné kódy 00 až 12 skryté v autotestovací nabídce místo na běžném displeji — Dual Boiler tak může trpět chybou, kterou jste na obrazovce nikdy neviděli.

## Jak si přečíst skrytý log chyb sám

Tabulky jsou servisní data, a tak vede cesta k historii stroje přes tytéž servisní obrazovky. Postupy mají technický nádech, ale opraváři je zdokumentovali důkladně:

- **Barista Touch a Oracle Touch** — vypněte stroj vypínačem v zásuvce, držte přední tlačítko Power a zároveň napájení zapněte, pusťte tlačítko při zobrazení loga, zadejte servisní heslo 00000 a otevřete Error Counter s uloženými chybami nebo Live Debug s živými teplotami a hladinami vody.
- **Barista Touch Impress** — stejná tlačítková sekvence, jen servisní heslo zní 02015.
- **Oracle BES980** — se zapojeným, ale vypnutým strojem podržte společně 1 CUP, 2 CUP a POWER alespoň na vteřinu; po dlouhém pípnutí stiskněte volič SELECT, otevře se Error Storage a chybami 1 až 32 lze listovat i s uloženými počty.

S obrazovkami zacházejte, jako by byly určeny jen ke čtení: poznamenejte si uložené hodnoty, nastavení nesahejte a log vymažte až po opravě, abyste poznali, zda se kód vrací. Při vlastní údržbě a drobných rozborkách se hodí i komunitní průvodce a rozklady na [ifixit.com](https://www.ifixit.com).

## Co opravy běžně stojí

I proti neveřejné tabulce zůstává ekonomika předvídatelná. Sestavy teplotních čidel se pohybují zhruba €25 až €95 podle konkrétního čidla (sondy parní páky a mléčné konvice patří mezi dražší), sady o-kroužků €10 až €20 a opravná sada mléčného čidla vyjde na €30 až €50 proti €80 až €95 za originální sestavu. Nabídky výrobce na vnitřní poruchy mimo záruku se běžně pohybují mezi €300 a €500, takže oprava na úrovni čidla v nezávislém servisu většinou vychází lépe. Majitelé strojů se štítkem Sage najdou pokrytí stejných tabulek ve [britské edici webu](https://cs.codefixcoffee.com/uk/).

### Koupě stroje Sage/Breville v Česku

V českých obchodech se stroje Sage a Breville objevují jen omezeně a většinou jde o dovoz z Británie či Německa. Napětí 230 V odpovídá naší síti, britské kusy ale mívají vidlici typu G, za kterou si opatřete pořádný adaptér, ne nejlevnější cestovní verzi. Počítejte také s tím, že záruka z britského e-shopu se po Brexitu v EU uplatňuje obtížně, takže si doklad o koupi pečlivě uschovejte.
