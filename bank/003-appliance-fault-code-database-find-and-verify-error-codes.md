---
title: Jak najít a ověřit chybový kód spotřebiče
description: Jak vypátrat chybový kód jakéhokoli spotřebiče – kde výrobci schovávají seznamy, jak ověřovat fóra proti servisní dokumentaci a pasti shodných kódů.
---

Kód na displeji je jen půlka odpovědi: říká, že stroj zaregistroval závadu, ale už ne, jaký díl kupovat. Jde o popis příznaku, který do stroje napsal programátor řídicí desky – a deska, která závadu zachytí, ji dokáže i zkreslit. Než si cokoli objednáte, potřebujete význam pro svou přesnou značku, kategorii spotřebiče a model, a to z více než jednoho zdroje.

## Výrobcem schválené seznamy existují, jen se špatně hledají

Překvapením bývá, jak často oficiální seznam vůbec neexistuje, nebo se skrývá tam, kde se majitelé nepodívají.

- Některé značky nezveřejňují nic. Myčky GE zobrazují C-kódy, H2O a 888, ale GE neprovozují žádnou oficiální stránku s chybovými kódy; mezeru zaplňují opravárenské weby. Kód 888 na myčce GE znamená závadu řídicí desky – od samotného GE se to nedozvíte.

- Některé značky informaci rozdělují na dvě vrstvy. Stroje De'Longhi většinou ukazují slova jako General Alarm, novější modely navíc logují číselné kódy 1101 nebo 1512, které běžně vidí jen technici; obě vrstvy najdete pohromadě na [stránce General Alarm a číselných kódů De'Longhi](https://cs.codefixcoffee.com/delonghi/magnifica-dinamica/general-alarm-code-1101-1512/).

- Některé značky zveřejňují jen přívětivou podmnožinu. Philips u espresso automatů zveřejňuje malou sadu uživatelsky opravitelných kódů a zbytek směruje na podporu, přestože i „servisní“ kódy mají rozpoznatelné příčiny.

- Když manuál tabulku obsahuje, sedí obvykle vzadu v kapitole o řešení problémů – jeden řádek na kód, bez názvů součástek a bez postupu opravy.

Informace většinou existují, jen musíte hledat dál než v rychlé příručce.

## Jak kód ověřit jako technik

### Zapište si přesně, co displej ukazuje

Zaznamenejte přesný řetězec, kategorii spotřebiče, úplné modelové označení z výrobního štítku a okamžik, kdy se kód objevuje. Jedna špatně odečtená číslice vás pošle do úplně jiného subsystému. „SE“ na sporáku nebo vestavné troubě Samsung značí uvíznutou klávesu v membráně dotykového panelu – viz [výklad kódu Samsung SE](https://cs.codefixcoffee.com/samsung/range-wall-oven/se/) – a podobně vypadající řetězce u jiných kategorií spotřebičů míří jinam.

Sledujte rovněž, zda kód vyskočí při startu, nebo uprostřed cyklu: startovní závady chytá autotest po zapnutí, mid-cyklové se týkají spíše toho, co právě běželo – čerpadla, topení nebo ventilu. Poznamenejte si i to, co kód odstraní. Trouby Samsung například kód na displeji podrží, dokud se neodstraní příčina, nebo dokud se na tři minuty nevypne jistič; celý běh kódů značky je indexovaný v [přehledu chybových kódů troub Samsung](https://cs.codefixcoffee.com/samsung-oven-error-codes/).

### Význam od výrobce má přednost

Než sáhnete po fórech, projděte kapitolu o řešení problémů v manuálu, servisní portál značky a servisní bulletiny ke svému modelu. Oficiální význam je výchozí čára a vše ostatní je komentář. Návody ke stažení nabízejí přímo weby výrobců, například [zákaznická podpora De'Longhi](https://www.delonghi.com/) nebo [podpora Philips](https://www.philips.com/).

### Fóra konfrontujte se servisní dokumentací

V diskusích se dozvíte, co se v praxi skutečně rozbíjí. Servisní tabulka prohlásí, že kód znamená „závadu varné jednotky“; fórum dodá, že na vašem modelu jde většinou o zaseknutý tabletek kávy a čtvrt hodiny čištění. Příspěvky berte jako důkazní materiál, ne jako pravdu:

- Váhu mají příspěvky, které jmenují váš přesný model a popisují opravu, která držela i po týdnech.

- Nedůvěřujte vláknu, které pro každý kód každého stroje doporučuje tentýž díl.

- Rozchází-li se fórum se servisním dokumentem, dokument vítězí ve významu a fórum v pravděpodobnosti.

## Past – stejný kód, jiný význam

Tady zabloudí většina vlastní diagnostiky, protože chybové kódy nejsou standardizované, a to ani mezi značkami, ani někdy v rámci jediné produktové řady.

- Stejné číslo, nesouvisející významy. U Jury je [Error 2](https://cs.codefixcoffee.com/jura/automatic-machines/error-2/) závada snímače kávového termobloku – anebo jen stroj příliš studený na to, aby topil. U Philips nebo Saeco je Error 02 interní závada směrovaná rovnou do servisu. Stejné číslo, stejná kategorie, jiné subsystémy i účty.

- Slova dokáží kódy zastřít. „General Alarm“ u De'Longhi má číselného dvojčete logovaného pro techniky; pořádná oprava vyžaduje znát obě vrstvy.

- Kategorie hraje roli stejně jako značka. Řetězec kódu na sporáku znamená na myčce nebo pračce téže značky něco jiného. Filtrujte nejprve podle typu spotřebiče a poté podle modelu.

Význam prověřte proti příznaku: topný kód na stroji, který topí, nebo odtokový kód na stroji, který odtéká, většinou znamená, že čtete špatný zápis – nebo zápis pro špatný model.

## Ověřovací seznam v pěti krocích

1. Vyfoťte displej a opište si úplné modelové označení z výrobního štítku.

2. Získejte význam od výrobce z manuálu nebo servisní dokumentace.

3. Potvrďte ho alespoň dvěma fórovými vlákny, která jmenují váš model a hlásí trvalou opravu.

4. Zkřížte význam s nezávislou referenční stránkou – například [chyba 11 nebo 19 u Philips](https://cs.codefixcoffee.com/philips-saeco/espresso-machines/error-11-or-19/) musí znít stejně bez ohledu na zdroj, a při rozporu věřte tomu, kdo cituje servisní dokumentaci.

5. Resetujte stroj jednou a rozhodněte se – vrátí-li se kód okamžitě, berte ho vážně a vybírejte mezi levným dílem, vyčištěním a technikem.

## Kdy s hledáním skončit

Zavřete záložky ve chvíli, kdy se dva nezávislé zdroje shodnou na významu a příznak mu odpovídá. Další čtení nezmění kód, který se po resetu okamžitě vrací – od té chvíle je rozhodnutí ryze praktické: cena dílu proti stáří stroje.

### Praktické tipy pro Česko

Návod k použití si pro většinu modelů stáhnete v češtině na webu výrobce podle typového označení ze štítku; tabulky kódů bývají schované až v závěrečné kapitole o řešení problémů. Do vyhledávače zadávejte kód vždy společně s kategorií spotřebiče – myčka nádobí, kávovar, trouba – protože shodný řetězec u různých kategorií oznamuje odlišnou závadu. A u stroje mladšího dvou let nezapomeňte na zákonnou záruku 24 měsíců, kterou se vyplatí probrat s prodejcem dřív, než začnete cokoli rozvrtávat.
