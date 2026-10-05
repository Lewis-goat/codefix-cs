---
title: Breville Dual Boiler 00–12: dvoumístné kódy
description: Breville Dual Boiler BES920 hlásí závady kódy 00 až 12 ve skryté servisní nabídce: co který blok znamená, pára versus vaření a jaké jsou opravy.
---

Espresso stroje Breville zpravidla oznamují závady na běžném displeji: Barista Touch ukazuje kódy ER, Oracle hlásí kódy „Error" a Oracle Jet pracuje s čísly E. **Dual Boiler BES920** to řeší jinak. Jeho přehled závad tvoří soubor prostých dvoumístných kódů, **00 až 12**, které najdete ve skryté servisní nabídce místo na každodenní obrazovce. Při sledování předního panelu za normálního dne na ně nenarazíte — musíte znát kombinaci tlačítek.

Číslování stojí za pozornost, protože tvoří přehlednou tabulku: blok, do něhož kód spadá, prozradí druh závady a uvnitř bloku pak kód jmenuje součástku, která si stěžuje.

## Jak přečíst protokol závad

Do protokolu se dostanete ze servisní nabídky:

1. Vypněte stroj u zásuvky.
2. Podržte **EXIT** a **MANUAL** a zároveň stroj znovu zapojte; na displeji se objeví servisní nabídka.
3. Tlačítkem **MENU** dojděte k položce 3, tedy k protokolu závad. Položka 4 zobrazuje stav hladiny v kotli jako LLL (nízká) nebo HHH (vysoká).
4. V protokolu závad pak tlačítkem **MENU** listujte mezi kódy 00 až 12; u každého je uložený počet výskytů.
5. U položky „ErSt" podržte **MANUAL** tak dlouho, dokud stroj nepípne — uložené kódy se vymažou, počítadlo šálků zůstává zachováno.

Počty výskytů vypovídají téměř tolik jako kódy samotné. Závada s počtem jedna z předloňska je uzavřenou historií; závada, jejíž počet týden co týden roste, je živý problém, který se teprve rozvíjí.

## Co pokrývá rodina kódů 00

Kódy **00 až 05** obsazují blok teplotních čidel, uspořádaný do tří dvojic. V každé dvojici znamená nižší číslo, že čidlo **není detekováno** — deska je vyhodnotí jako přerušený obvod — a vyšší číslo pak **zkrat**:

- **00 a 01** — teplotní čidlo parního kotle, nejprve nedetekováno, poté zkrat.
- **02 a 03** — teplotní čidlo kávového kotle, nejprve nedetekováno, poté zkrat.
- **04 a 05** — teplotní čidlo vyhřívané vařicí hlavy, nejprve nedetekováno, poté zkrat.

BES920 má dva nerezové kotle a navíc vyhřívanou vařicí hlavu, takže tři čidla pokrývají tři vyhřívané zóny stroje. [Stránka kódu 00](https://cs.codefixcoffee.com/breville/dual-boiler-bes920/00/) se věnuje čidlu parního kotle, její praktické rady ale platí i pro zbývajících pět kódů: před nákupem dílů znovu zasuňte a prohlédněte konektor čidla a hledejte vlhkost, protože voda přemostěním kontaktů se projeví jako přerušení, nebo jako zkrat — podle toho, jak zrovna sedí. Originální sady NTC čidel stojí podle typu zhruba 25 až 90 €; sady těsnících kroužků za 10 až 20 € přitom bývají stejně často pravým viníkem.

## Parní strana versus vařicí strana

Zbytek tabulky se dělí po stejné linii jako dvojice čidel:

- **Parní kotel:** 06 (potíže s čerpadlem během startu), 07 (hladina vody nebo závada čerpadla) a 11 (zjištěné přehřátí).
- **Kávový kotel, tedy vařicí strana:** 08 (problém čerpadla nebo průtoku), 09 (závada hladiny vody) a 10 (zjištěné přehřátí).
- **Vařicí hlava:** 12 (zjištěné přehřátí).

### Kódy, které se vyskytují společně

Tyto závady se navzájem provazují, a proto čtení celého protokolu přináší víc než čtení jediného kódu. Kód 08 říká, že čerpadlo běželo, ale průtokoměr nezaregistroval nic — nejčastěji za tím stojí kámen na lopatkách průtokoměru nebo drobné čerpadlo, které bzučí, avšak vodu nepohání, a v obou případech je prvním krokem odvápnění. Kód 11, tedy přehřátí parního kotle, obvykle následuje kotli, který se nedoplňuje — podívejte se, zda počty nenashromáždily i kódy 07 nebo 08 — protože topné těleso dál ohřívá málo naplněný kotel; druhou příčinou bývá netěsnící těsnění hladinové sondy. Než cokoli objednáte, přečtěte si položku 4 servisní nabídky: stav hladiny, který odporuje tomu, co slyšíte při plnění stroje, napoví, na které straně závada ve skutečnosti je.

Kód 12, přehřátí vařicí hlavy, patří k vzácnějšímu konci tabulky a právě u něj má opakovaný výskyt největší váhu — přehřátí, které se pořád vrací, ukazuje spíše na napájecí desku držící ohřev trvale sepnutý než na drift čidla. Podrobný rozbor přináší [stránka kódu 12](https://cs.codefixcoffee.com/breville/dual-boiler-bes920/12/).

### Nákup a servis v Česku

V Evropě se tento stroj prodává pod značkou Sage, takže příručky, díly i servisní pokyny hledejte pod názvem Sage Dual Boiler — s označením Breville v českých podmínkách prakticky nenarazíte. Koupíte-li stroj v Česku jako spotřebitel, můžete uplatňovat 24měsíční zákonnou záruku, a to i u vad, které se přihlásí později v jejím průběhu. Podporu a uživatelské příručky evropské verze značky najdete na [sageappliances.co.uk](https://www.sageappliances.co.uk/).

## Kolik stojí díly

- Odvápněný prostředek na kódy průtoku a hladiny: zhruba 10 €, a opravdu část z nich vyřeší.
- Plnicí čerpadlo: 30 až 60 €.
- Hladinová sonda parního kotle se sadou kroužků: kolem 85 €; samotné sady kroužků 10 až 20 €.
- Tepelná pojistka: 10 až 20 € — nejdřív ale zjistěte, proč se přetavila.
- Triak či napájecí deska: 80 až 150 €.

Cenové nabídky servisu na vnitřní závady mimo záruku se u této značky běžně pohybují od 300 do 500 € výš, takže výměna čerpadla nebo čidla se svépomocí vyplatí; u desky ve starším stroji si nejdříve vyžádejte odhad. Voda a síťové napětí se potkávají v horní části kotle — proto před prací se sondami stroj odpojte ze zásuvky.

Jak formulují své kódy ostatní stroje značky, ukazuje [sekce Breville](https://cs.codefixcoffee.com/breville/) — stroje s kódy ER sdílejí diagnostické myšlenky, číslování už ne.
