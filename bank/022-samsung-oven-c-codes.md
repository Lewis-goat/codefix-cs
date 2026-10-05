---
title: Kódy C u troub Samsung – rodina teplot chytrých sporáků
description: Trouby Samsung a kódy C-21, C-24 a C-F2 – přehřátí dutiny, rychlý nárust teploty u ventilace a zpětná vazba chladicího ventilátoru. Postupy a ceny dílů.
---

Sporáky a vestavné trouby Samsung — řady NE a NX a jejich příbuzní NV a NZ — mluví dvěma „dialekty" chyb. Dvojité kódy jako E-08 nebo E-27 pokrývají topné části trouby, krátké kódy jako SE a tE hlásí potíže ovládacího panelu. Mezi nimi stojí rodina C: C-21, C-24 a C-F2, tedy teplotní a ventilační kódy sledované v [rejstříku kódů troub Samsung](https://cs.codefixcoffee.com/samsung-oven-error-codes/). Právě těm věnujte nejvíc pozornosti — alespoň jeden z nich znamená, že se trouba doopravdy přehřála. Oficiální podklady k servisu najdete u [zákaznické podpory Samsung](https://www.samsung.com/cz/support/).

## Rejstřík chyb tu nenajdete

Samsung u troub nezpřístupňuje žádný uživatelský chybový log. Kód zůstává na displeji, dokud neodstraníte příčinu, nebo dokud nepřerušíte napájení jističem — u procedur rodiny C počítejte s pěti až deseti minutami. Vrátí-li se kód i po resetu, berte ho jako skutečnou závadu, ne jej resetujte znovu a doufejte v náhodu.

### Pro české podmínky

Vestavné trouby bývají u nás standardně napojené na vlastní jistič v bytovém rozvaděči, takže reset provádějte tam, ne manipulací se zástrčkou. Při zabudování do starších kuchyňských skříněk si ověřte také vůle podle instalačního manuálu — těsné obezdění bez prostoru pro ventilaci přehřívá elektroniku a přispívá ke kódům C-24 i C-F2.

## C-21: odstávka při přehřátí

[C-21](https://cs.codefixcoffee.com/samsung/range-wall-oven/c-21/) oznamuje, že bezpečnostní monitor zaznamenal vnitřní teplotu trouby mimo bezpečné pásmo a deska proto zastavila topení. Uživatelé popisovali sporáky, které se před zobrazením kódu nebezpečně rozpálily — jde tedy o signál k zastavení pečení, ne o drobnost. Nejčastějším viníkem je teplotní čidlo dutiny nebo jeho kabeláž; hlavní deska PCB je až druhým podezřelým.

1. Vypněte jistič na pět až deset minut a jedenkrát troubu otestujte. Vrátí-li se C-21 při dalším nahřívání, jde o skutečnou závadu.
2. Odpojte sporák, vyšroubujte dva šrouby držící sondu čidla na zadní stěně dutiny a vytáhněte kabeláž dopředu, abyste ji mohli odpojit.
3. Změřte čidlo multimetrem: při pokojové teplotě je zdravé zhruba při 1 080 Ω. Rozepnutý obvod nebo jasně nesmyslná hodnota znamená výměnu.
4. Prohlédněte konektor kabeláže v místech, kde prochází poblíž topného tělesa — přepálený konektor vyvolá tentýž kód.
5. Je-li čidlo v pořádku a trouba stále hlásí závadu, deska špatně reguluje topné těleso; to je oprava na úrovni servisu.

## C-24: kontrola rychlého nárůstu

[C-24](https://cs.codefixcoffee.com/samsung/range-wall-oven/c-24/) se detekuje v okolí ventilace a prostoru s elektronikou: oddělení s deskami se ohřívá rychleji, než deska očekává. Samsung uvádí rodinu C-24 a C-25 jako přehřátí topení ve vztahu k této ventilační oblasti. V praxi se příčina rozdělí tři směry — chladicí ventilátor, který se nikdy nerozběhne, zablokovaný průtok vzduchu kolem sporáku nebo stárnoucí nadteplotní termistor, který zdravou oblast hlásí jako přehřátou.

Diagnostika spočívá hlavně v poslechu a pohledu. Po resetu jističe spusťte pečení a zaposlouchejte se, zda konvekční i chladicí ventilátor při nahřívání trouby nastupují; ticho je jasná odpověď. Zkontrolujte instalační vůle a to, zda skříňky, alobal nebo prach neblokují větrací otvory pod i za sporákem. S vypnutým napájením lze nadteplotní termistor přeměřit na jeho konektoru — leží ve stejné třídě zhruba 1 000 Ω jako čidlo dutiny a rozepnutý nebo „plující" kus patří k výměně. Je-li ventilátor mrtvý, vyměňte jej dřív, než se upeče řídicí deska: teplo je příčina a deska je jen oběť.

## C-F2: zpětná vazba chladicího ventilátoru

[C-F2](https://cs.codefixcoffee.com/samsung/range-wall-oven/c-f2/) vypadá jako kód přehřátí, většinou ale není. Rodina C-F znamená, že sledovaná komponenta se nehlásí, a u C-F2 jde o obvod chladicího ventilátoru: deska displeje nedostává zpětný signál, který očekává. Buď ventilátor opravdu nestartuje, nebo má uvolněný či přepálený konektor, nebo selhala linka zpětné vazby k desce.

Postupujte popořadě. Po resetu jističe troubu zahřejte a ověřte, zda se vrtule ventilátoru fyzicky točí. Točící se ventilátor s trvajícím kódem ukazuje na zpětnou vazbu — přesaďte konektor ventilátoru na desce a hledejte tepelně zabarvené piny. Tichý ventilátor znamená kontrolu zaseknuté vrtule (prach nebo spadlý šroub za panelem) a následně měření vinutí na rozepnutý obvod. Opravy ventilátoru a konektoru jsou levné; C-F2, který přežije obě prověrky, směřuje na vstup hlavní desky.

## Kolik stojí díly

Teplotní čidlo dutiny stojí 15–40 € a jeho výměna je práce na deset minut se šroubovákem — jde o nejčastější opravu celé rodiny. Chladicí ventilátor vyjde na 40–90 €, kabeláž na 10–20 €. Drahou položkou je hlavní deska PCB za 150–300 € a po jejím nákupu byste se měli ohlížet až po ověření čidla i ventilátoru. Návštěva technika stojí zhruba 120–250 € za diagnostiku plus díl; u sporáku mimo záruku se závadou na úrovni desky je rozumné nejdřív získat tuto nabídku a teprve pak objednávat díly.

Pro celou rodinu platí jediné pravidlo — C-21 opakovaně neresetujte a dál nepečte. Kód znamená, že deska už zaznamenala teplotu, která se jí nelíbila, a další překročení může být výš na stupnici.
