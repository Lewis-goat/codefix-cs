---
title: "Chyby 1 až 5 u Jura: celá rodina kódů kolem termobloku"
description: "Chyby 1–5 u přístrojů Jura se týkají termobloků, jejich NTC čidel a pojistkových kordů. Který kód patří ke kterému dílu a past zvaná chyba 2."
---

Pět kódů 1 až 5 může působit jako náhodná hrstka čísel, ale všechny spojuje jediné téma: teplo. Každý z nich se váže buď k termoblokům — kompaktním průtokovým ohřívačům, které připravují vodu na kávu a páru —, nebo k čidlům a pojistkovým kordům, které tyto bloky střeží. Jakmile se naučíte tuto rodinu číst, řekne vám kód, který ohřívač zlobí a zda jde o problém měření, teploty nebo napájení.

## Dva ohřívače, pět kódů

V přístroji Jura pracují dva termobloky. Kávový ohřívá vodu pro přípravu kávy, parní obsluhuje stranu páry a horké vody. Každý z nich nese NTC čidlo — rezistor, jehož odpor se mění s teplotou — které se hlásí řídicí desce, a každý chrání pojistkové kordy, jež při přehřátí přeruší napájení. Kódy 1 až 5 jsou způsob, jakým deska oznamuje, že jeden z těchto prvků nefunguje, jak má:

- **Chyby 1 a 2** míří na obvod čidla kávového termobloku.
- **Chyby 3 a 4** míří na parní termoblok — ten hlásí příliš nízko, nebo se přehřívá.
- **Chyba 5** znamená, že samotné topné těleso nedodává výkon.

## Kódy na kávové straně

### Chyba 1: závada čidla kávového termobloku

[Chyba 1](https://cs.codefixcoffee.com/jura/automatic-machines/error-1/) znamená, že deska nedokáže z teplotního čidla kávového termobloku přečíst smysluplnou hodnotu. U řad S, X, J a Z jde o klasickou poruchu čidla, u modelů F a E80 typicky o čidlo mechanicky poškozené. Zvláštnost, kterou se vyplatí znát: stroj přivezený z rozmrzlého auta nebo z nevytápěné garáže může kód vyhodit, aniž by cokoli bylo skutečně rozbité. Objeví-li se na zahřátém stroji a po restartu se okamžitě vrací, je obvod čidla přerušen — v úvahu připadá čidlo, jeho kabel nebo pojistkové kordy napájející blok.

### Chyba 2: přerušené čidlo — nebo jen studený stroj

[Chyba 2](https://cs.codefixcoffee.com/jura/automatic-machines/error-2/) je nejčastější kód Jura vůbec a má dvě tváře. Ta neškodná: stroj je chladnější než zhruba 10 °C a ohřívač je záměrně blokován, dokud se neprohreje — typické u přístrojů doručených v zimě nebo stojících v chladné místnosti. Ta vážná: čidlo kávového termobloku nebo pojistkové kordy mají přerušený obvod.

Diagnostikou je právě zahřátí na pokojovou teplotu. Osvědčený postup: pět minut foukejte fénem na nejnižší stupeň do dutiny nádrže na vodu, nebo nádrž naplňte vlažnou (nikoli horkou) vodou, a poté stroj restartujte. Kód zmizel? Nic není rozbité, jen přístroj umístěte do teplejší místnosti. Přetrvává-li i na zahřátém stroji, je obvod čidla přerušený a uvnitř je nutné prověřit NTC čidlo společně s pojistkovými kordy.

## Kódy na parní straně

### Chyba 3: parní termoblok hlásí málo

[Chyba 3](https://cs.codefixcoffee.com/jura/automatic-machines/error-3/) je parní obdobou chyby 1: parní termoblok nehlásí teplotu, ať už kvůli svému čidlu, kabelu, nebo proto, že je stroj stále ještě příliš studený. Jedna poznámka navíc: silná vrstva vodního kamene zpomaluje ohřev natolik, že některé verze firmwaru na ni zareagují kontrolou — plné odvápnění proto zařaďte na seznam dřív, než se začne cokoli rozebírat. Uvnitř stroje si prohlédněte kabel čidla v místě, kde se nejčastěji ohybá.

### Chyba 4: parní termoblok se přehřívá

[Chyba 4](https://cs.codefixcoffee.com/jura/automatic-machines/error-4/) je kód, který je potřeba brát vážně. Parní termoblok překročil teplotu, kterou deska očekávala — buď čidlo ukazuje méně, než je skutečnost (izoluje jej kámen, kontakty jsou zkorrodované), nebo napájecí deska nepřerušila přívod k ohřívači. Jura samotná uvádí chyby 2 a 4 jako své dvě nejčastější opravy. Po vychladnutí a odvápnění se jako první vyměňuje čidlo; přehřívá-li se blok i s novým NTC čidlem, znamená to, že napájecí deska ohřívač nevypíná, a je ji nutné vyměnit (počítejte se 120 až 250 €). Ohřívač, který nelze vypnout, představuje požární riziko: dokud je tento kód aktivní, nenechávejte stroj zapnutý bez dozoru.

### Chyba 5: ohřívač nedosáhne teploty

[Chyba 5](https://cs.codefixcoffee.com/jura/automatic-machines/error-5/) říká, že ohřívač běžel, ale teplota ani po čase nestoupla. U přístrojů Jura to téměř vždy znamená pojistkové kordy chránící termoblok, které vyhoří po předchozím přehřátí nebo prostě vysokým věkem; druhou možností je mrtvé topné těleso samotného termobloku. Spouštěčem může být i velmi studený stroj, proto jej nejdřív zahřejte. Uvnitř změřte oba kordy i těleso: co měřič ukáže jako rozpoj, je dílem k výměně — a poté zjistěte, proč pojistky vůbec vyhořely (kámen, zaseknuté relé nebo chod nasucho po vyprázdněné nádrži).

## Co mají všechny kódy společné

V celé této rodině se opakují dva hlavní aktéři: pojistkové kordy a NTC čidla. Originální NTC čidlo Jura stojí přibližně 25 až 40 €, sada pojistkových kordů 15 až 30 € a termoblok 90 až 180 €. Když už se čidlo mění, zkučení servisní technici vyměňují kordy ve stejném okamžiku. A jeden vzorec je klíčový: pojistkový kord, který vyhoří znovu během několika dní, neznamená smůlu na nový díl, ale to, že napájecí deska drží ohřívač trvale zapnutý.

Pamatujte také, že skříně Jura drží bezpečnostní šrouby a termobloky jsou pod síťovým napětím — pokud na takovou práci nejste vybaveni, patří tato rodina kódů na servisní stůl. U modelů S, Z, GIGA a novější řady E se oprava téměř vždy vyplatí; u deset let staré Impressy zvažte, zda nestojí za srovnání s repasovaným kusem. Kontext celé řady nabízí [přehled chybových kódů Jura](https://cs.codefixcoffee.com/jura/), oficiální dokumentaci pak [podpora na jura.com](https://www.jura.com/) a rozklady přístrojů [servisní návody na iFixit](https://www.ifixit.com/).

### Zima v českých podmínkách

Chyba 2 má u nás výrazný sezónní rozměr: kávovary objednané mezi listopadem a únorem putují dodávacími službami v nevytápěných automobilech a pak často končí v chladné chodbě. Než nový stroj poprvé zapnete, nechte jej alespoň dvě až tři hodiny aklimatizovat při pokojové teplotě. A pokud přístroj přezimovává na chatě nebo v garáži, s prvním šálkem počkejte, dokud se řádně neprohreje — ušetříte si zbytečnou cestu do servisu.
