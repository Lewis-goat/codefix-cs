---
title: Pára a kódy u Breville/Sage Oracle: co zkoušet jako první
description: Co znamenají parní chybové kódy u Breville/Sage Oracle, purge rutina, kterou zkuste jako první, a kdy je skutečným viníkem vodní kámen.
---

Parní strana stroje Breville Oracle je jeho nejvytíženější místo: nerezový parní kotel, automaticky šlehající páka, hladinové sondy i plnicí čerpadlo, každý den v provozní teplotě. Zároveň generuje velkou část všech chybových kódů stroje. Rodina Oracle používá 32položkovou servisní tabulku, kterou Breville nezveřejňuje, a ve Velké Británii nese tentýž hardware odznak **Sage** — kódy jsou identické. Než usoudíte, že se rozbil díl, projděte levné kontroly: většina parních zastavení je ucpaná špička páky, vynechaný purge nebo kámen na sondě.

## Kde se parní kódy v tabulce Oracle nacházejí

Oracle (BES980) a Oracle Touch (BES990) sdílejí jednu tabulku; BES980 zobrazuje položky jako „Error 1“ až „Error 32“, BES990 s předponou ER. Parní položky se shlukují na pěti místech:

- **Error 1 až 4** — teplotní čidlo parního kotle: přerušení obvodu při startu, ztráta signálu za provozu a zkrat v obou situacích. Jedno čidlo, čtyři způsoby, jak se přihlásit.
- **Error 13 až 16** — táž čtveřice pro čidlo samotné parní páky, tedy sondu, která ukončí šlehání mléka při správné teplotě. Bydlí na nejvlhčím místě stroje.
- **Error 18** — parní kotel se nezahřívá tak, jak má.
- **Error 20 a 21** — hladina vody v parním kotli nebo potíže s plnicím čerpadlem a údaj hladinové sondy, který neodpovídá očekávání desky.
- **Error 26** — parní kotel se přehřál nad cílovou hodnotu; **Error 32** znamená únik z parního kotle nebo selhání doplnění vody.

Ne všechno poblíž páky je přitom parní záležitost: kódy 5 až 8 patří čidlu kávového kotle a [Error 8](https://cs.codefixcoffee.com/breville/oracle-bes980/error-8/) je jeho položkou zkratu za provozu. Rozlišit rodiny pomůže čtení uloženého logu — na BES980 podržte spolu 1 CUP, 2 CUP a POWER u vypnutého stroje, otevře se Error Storage a všemi 32 kódy projdete i s počty výskytů.

## První pokus: purge

Slabá nebo stříkající pára, případně kód těsně po mléčném nápoji, většinou ukazuje na špičku páky, nikoli na kotel:

1. Odpojte stroj od napájení a nechte páku vychladnout.
2. Odšroubujte parní špičku a namočte ji do horké vody s trochou odvápňovacího přípravku; každý otvor prostřelte jehlou z čistícího náčiní.
3. Proveďte purge — zhruba deset sekund páry do odkapávací misky bez špičky a poté znovu s nasazenou špičkou.
4. Odteď páku pročišťujte po každém šlehání mléka; zaschlé mléko v špičce je začátkem většiny těchto zastavení.

Sleduje-li stroj parní tlak, jako Oracle Jet kódem E16, může ztvrdlá špička spustit chybu dřív, než vůbec zaregistrujete, že pára slábne.

## Tvrdost vody, kámen a hladinové sondy

Kde je tvrdá voda, tam si kámen píše vlastní chybové kódy. Hladinové sondy parního kotle trvale sedí v horké vodě a kamenný povlak je elektricky izoluje, takže deska čte „bez vody“, i když je kotel plný — to je klasická cesta k Error 20 či 21 i k selhání doplňování u Error 32. Kámen se navíc ukládá v celé cestě páry a na sání plnicího čerpadla. Kompletní odvápnění včetně cyklu parního kotle je nejlevnější diagnostika, jakou můžete spustit, a samo o sobě maže překvapivou část těchto kódů.

Potvrzuje to i příbuzný model rodiny: Dual Boiler skrývá kódy 00 až 12 v autotestovací nabídce a [kód 00](https://cs.codefixcoffee.com/breville/dual-boiler-bes920/00/) — čidlo parního kotle nedetekováno — stojí v čele tabulky, jejíž položky hladiny a plnění se pod tvrdou vodou chovají úplně stejně.

## Kdy odvapňovat a kdy rozebírat

Nejprve odvápnění, teprve potom rozborka — ale mějte na paměti, kde odvápnění přestává pomáhat:

- **Odvápňete nejprve** u kódů hladiny, sondy a doplňování (20, 21, 32), u slabé páry bez kódu a u každého stroje, kterému od posledního cyklu uběhly více než tři měsíce. Náklad: jedna láhev odvápňovače.
- **Odvápnění nevyřeší** kód čidla, který se okamžitě vrací na čerstvě odvápněném zahřátém stroji — ať už jde o parní položky 1 až 4, nebo [Error 8](https://cs.codefixcoffee.com/breville/oracle-bes980/error-8/) na kávové straně. Kód, který odvápnění přežije, míří na čidlo, jeho kabel nebo konektor.
- **Zastavte se a zkontrolujte těsnění**, opakuje-li se Error 26: prosakující o-kroužek parní sondy nechává hřát kabel čidla a napodobuje zbloudilý kotel. Nové o-kroužky sondy jsou levné; triaková deska, která nedokáže vypnout ohřev, nikoliv.
- **Error 18** u stroje, který už páru vůbec neohřívá, bývá na straně topení — tepelná pojistka, topné těleso nebo deska — nikoli na kameni, takže jde o opravu, ne o úklid.

## Kolik stojí díly

Originální sestavy teplotních čidel se pohybují zhruba €25 až €95 podle konkrétního čidla; sestavy parní páky s integrovaným čidlem okolo €60 až €95; sonda se sadou o-kroužků cca €85 a plnicí čerpadlo €30 až €60. Proti tomu se nabídky výrobce na vnitřní poruchy mimo záruku běžně pohybují mezi €300 a €500, takže láhev odvápňovače jako první krok a výměna čidla jako druhý je téměř vždy lepší počet. Majitelům strojů Sage je k ruce [britská edice webu](https://cs.codefixcoffee.com/uk/) a oficiální postupy údržby na [sageappliances.co.uk](https://www.sageappliances.co.uk).

### Tvrdá voda v ČR

Vodovodní voda je ve většině České republiky středně tvrdá až tvrdá, takže parní kotel Oracle je tady vystaven kameni intenzivněji než v mnoha oblastech západní Evropy. Nádržku proto plňte filtrovanou vodou a odvápnění provádějte alespoň v intervalech doporučených výrobcem — kódům 20, 21 a 32 se tím vzdálíte nejlevnějším možným způsobem.
