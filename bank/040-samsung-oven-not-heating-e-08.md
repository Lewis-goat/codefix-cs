---
title: Trouba Samsung se neohřívá: E-08 a jeho příbuzní
description: Trouba Samsung se neohřívá a hlásí E-08? Nejprve reset jističem, pak kontrola topného tělesa, čidla a relé i varianta se zámkem dveří.
---

Trouba, která běží, ale zůstává studená, selhává překvapivě předvídatelným způsobem: deska nastavila teplotu, prostor trouby se neohřál a stroj si důvod zapsal do paměti. U sporáků a vestavěných troub Samsung je [E-08](https://cs.codefixcoffee.com/samsung/range-wall-oven/e-08/) hlavním kódem pro tento stav — trouba se neohřívá a podezřelými jsou spodní či horní topné těleso, teplotní čidlo nebo relé na desce. Kolem něj se nachází malá rodina příbuzných kódů, které závadu dále upřesňují. Tento článek je prochází v pořadí, které se vyplatí dodržet, a začíná u kroku, který lidé nejčastěji vynechávají.

## Nejdřív reset jističem

Než učiníte jakýkoli závěr, vypněte na tři minuty jistič a poté jej zapněte zpět. Není to pověra — deska sporáku, která se dostala do vadného stavu, si může zapsat topnou závadu, kterou za normálních okolností neměla, a čistý restart cyklu ji vymaže. Vrátí-li se E-08 při dalším pokusu o pečení, závada je skutečná a pokračujte dál. Tentýž třiminutový reset otevírá diagnostickou cestu téměř ke všem kódům ze [seznamu kódů troub Samsung](https://cs.codefixcoffee.com/samsung-oven-error-codes/), proto se vyplatí si na něj zvyknout.

## Topné těleso

Spodní topné těleso je nejnamáhanější součást dole v troubě a jeho selhání je vidět pouhým okem. Při zapnuté troubě by mělo těleso rovnoměrně žhnout po celé délce. Viditelné přerušení, puchýř nebo spálené místo na povrchu je diagnóza, ke které nepotřebujete nářadí: těleso vyměňte. Představuje investici 30 až 60 € a patří k nejziskovějším opravám trouby vůbec. Září-li těleso v pořádku, ale trouba přesto neudrží teplotu, je zproštěno viny a na řadě je čidlo — celý postup rozhodování najdete na [diagnostické stránce E-08](https://cs.codefixcoffee.com/samsung/range-wall-oven/e-08/).

## Teplotní čidlo

Sonda čidla měří teplotu v prostoru trouby a hlásí ji desce formou odporu. Zdravé čidlo ukazuje při pokojové teplotě zhruba 1080 ohmů — a to jediné číslo představuje celý test:

1. Vypněte napájení jističem.
2. Odšroubujte sondu ze zadní stěny trouby (dva šrouby) a odpojte ji.
3. Změřte ji: zhruba 1080 ohmů při pokojové teplotě znamená zdravé čidlo.
4. Vyjde-li hodnota správně, zástrčku znovu pevně připoďte; při výrazné odchylce čidlo vyměňte.

Dva příbuzné kódy prozradí, kterým směrem čidlo selhalo, i bez měřidla. E-27 znamená, že čidlo čte jako přerušené — odpor je příliš vysoký, přes zhruba 2950 ohmů — což znamená vadnou sondu nebo uvolněnou zástrčku. E-28 naopak znamená zkrat, pod zhruba 930 ohmů, tedy zkratovanou sondu nebo přiskřípnutou kabeláž za troubou. V obou případech samo čidlo stojí 20 až 40 € a našroubuje se zevnitř trouby.

## Relé na desce

Září-li topné těleso správně a čidlo měří v normě, zbývá reléová deska: deska nepřepíná napětí k tělesu. Relé, které se nikdy nezavře, vypadá z pohledu trouby přesně jako mrtvé těleso. To je výsledek za 100 až 200 € a u staršího sporáku jde o moment, kdy dává smysl porovnat nabídku opravy se zbývající hodnotou přístroje.

## Varianta se zámkem dveří

Jedna výhrada před nákupem dílů: u některých modelů uvádí oficiální podpora Samsung E-08 jako závadu zámku dveří, nikoli ohřevu — jedná se o motorický zámek používaný při samočistícím cyklu, ne o topný okruh. Před objednáním tělesa si proto prověřte příručku ke svému modelu, kterou najdete v sekci podpory na [samsung.com](https://www.samsung.com/). Příbuzným kódem pro potíže se zámkem je E-0E (zobrazovaný jako E-0E nebo FL), který se obvykle objeví po samočistícím cyklu, když zasekne spínač zámku nebo selže motor zámku; celá sestava stojí 40 až 90 €. V žádném z těchto případů dveře násilím neotvírejte — nechte troubu zcela vychladnout, protože za horka se odemknout nedá.

## Kód, který znamená opačný problém

Pokud už se v této rodině závad pohybujete, znáte i [E-0A](https://cs.codefixcoffee.com/samsung/range-wall-oven/e-0a/): trouba se přehřívá. Vypadá jako zcela jiný problém, ale sdílí dva podezřelé s E-08 — čidlo, které čte špatně (tentokrát nižší hodnoty), nebo relé zaseknuté v sepnuté poloze, takže topné těleso nelze vypnout. E-0A řešte s větší naléhavostí než závadu bez ohřevu: zaseknuté relé znamená, že těleso zůstává trvale zapnuté, proto ihned vypněte jistič a troubu do dokončení opravy nepoužívejte.

## Kolik opravy stojí

Topné těleso 30 až 60 €, teplotní čidlo 20 až 40 €, sestava zámku dveří 40 až 90 €, reléová deska 100 až 200 €. Těleso a čidlo jsou u přístroje jakéhokoli rozumného stáří jasnou ano-volbou; u desky už jde o úsudek. Výjezd technika přijde na 120 až 250 € za diagnózu plus díl, což jsou férové peníze za potvrzení, který ze tří dílů opravdu potřebujete.

### Tipy pro české majitele

Než objednáte díl, opište si přesné označení modelu ze štítku — najdete jej zpravidla na rámu trouby hned po otevření dveří — protože topná tělesa a čidla se mezi modely Samsung liší. Běžné díly, jako tělesa, čidla či sestavy zámku, skladem drží české e-shopy s náhradními díly na bílou techniku, takže se můžete vyhnout čekání na zásilku ze zahraničí. Přístroj koupený v Česku navíc spadá pod 24měsíční zákonnou záruku, na kterou lze vadné relé či čidlo uplatnit, nevznikla-li vada nesprávným užíváním.
