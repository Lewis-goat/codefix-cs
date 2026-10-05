---
title: "Kódy F u kávovarů Miele: základní průvodce pro majitele CM a CVA"
description: "Jak fungují F-kódy u kávovarů Miele CM a CVA, které závady dodávky vody zvládnete sami a proč F77 a vnitřní chyby patří do rukou servisu."
---

## Jak sebediagnostika Miele pracuje

Stolní přístroje Miele CM i vestavné kávové systémy CVA neustále sledují vlastní plnící cykly, ventily a vařicí hardware a kdykoli sebediagnostika selže, nahlásí to jako kód F. Filozofie celé tabulky je neobvykle srozumitelná: kódy se dělí na závady věcí, kterých se fyzicky dosáhnete — nádržka na vodu, přívodní hadice, filtr — a na závady uvnitř stroje, kde je odpovědí manuálu restart následovaný servisem Miele.

Ta hranice je vynucená, ne doporučená. Miele výslovně uvádí, že vnější kryt nesmí být otevírán: stroje ukrývají vnitřní napětí a tlakový systém. Skutečným uměním majitele proto není diagnóza součástek, ale triáž — poznat, které kódy jsou vaše a které patří servisní lince. Modely se uvnitř liší (stolní CM 5510 či 6150 je jiný stroj než vestavná CVA 6401 nebo 6805), přístup ke kódům F je ale sdílený, a proto se průvodce hodí pro celou nabídku. Kompletní přehled najdete v naší [sekci Miele](https://cs.codefixcoffee.com/miele/).

## Přátelský konec tabulky: kódy F10 a F17

F10 a F17 sdílejí jediný zápis v manuálu a jeho znění stojí za zapamatování: neteče žádná, nebo jen velmi málo vody. Stroj se pokusil naplnit a buď zcela selhal, nebo voda jen slabě tekla. Jde o nejpřátelštější rodinu celé tabulky, protože postup z manuálu je téměř vždy celou opravou.

Kam se podívat nejdřív, záleží na typu stroje:

- **Stolní stroje CM:** příčinou je téměř vždy vyjímatelná nádržka — prázdná, špatně vsazená, nebo s ventilem, který se zasekává.
- **Vestavné stroje CVA připojené na vodovod:** podezření se stěhuje proti proudu, k uzavíracímu ventilu a filtru v přívodu vody.

Opravná sekvence je u obou krátká:

1. Vyjměte nádržku, naplňte ji čerstvou studenou vodou z vodovodu (ne destilovanou) a vraťte ji až do zajištění — to je postup z manuálu, téměř doslova.
2. Zkontrolujte sedlo ventilu nádržky, zda se v něm nezaseklo nebo neznečistilo těsnění, a propláchněte ho pod tekoucí vodou.
3. U strojů na vodovod ověřte, že uzavírací ventil je úplně otevřený a filtr v přívodu není ucpaný.
4. Vrátí-li se závada, odvápněte přívod vody — kámen v ventilu dělá z této závady záležitost občasnou, ne trvalou.
5. Stroj, který kód hlásí i při ověřené dodávce vody, potřebuje zásah servisu Miele na přívodním ventilu nebo čerpadle.

Náklady jsou minimální: obvykle €0, přívodní ventil zhruba €30 až €60, pokud skutečně selhal. Náš [detailní popis F10 a F17](https://cs.codefixcoffee.com/miele/cm-cva-machines/f10-f17/) rozebíhá kontroly nádržky i instalace do hloubky.

## Servisní hranice: F77 a vnitřní závady

Na druhém konci tabulky sedí F77, obecný kód Miele pro vnitřní závadu zjištěnou při startu — v praxi nejčastěji ventilový systém, který se nepodařilo inicializovat. Manuál je k hranicím samopomoci upřímný:

1. Vypněte přístroj senzorem zapnutí/vypnutí a odpojte ho ze zásuvky.
2. Nechte ho vypnutý několik minut; vrátila-li se F77 i po krátkém vypnutí už dříve, dopřejte mu až hodinu.
3. Znovu zapojte a zapněte a sledujte, zda se závada objeví okamžitě při inicializaci, nebo až při objednávce nápoje.

F77, která se po pokusu o restart vrátí, je selhání součástky — ventilu, čerpadla nebo řídicí desky — a jednoznačně patří servisu Miele. Před volbou si poznamenejte číslo modelu, protože CM a CVA jsou uvnitř odlišné a servisní linka se na ně zeptá. Co zkontrolovat a co čekat shrnuje naše [referenční stránka F77](https://cs.codefixcoffee.com/miele/cm-cva-machines/f77/); kontakty na servis najdete na [miele.com](https://www.miele.com/).

## Triažní pravidlo, které si zapamatujete

Širší rodina F přesahuje tyto dva záznamy a zahrnuje i ventily a varnou jednotku, které leží za stejnou servisní hranicí jako F77. Místo memorování tabulky si osvojte jediné pravidlo: zahrnuje-li oprava vodu, kterou vidíte — nádržku, přívodní ventil, filtr — je vaše a kroky z manuálu ji vyřeší. Vyžadovala by otevření stroje, nebo se kód vrací po úplném restartu, patří Miele.

Ekonomika oprav toto rozdělení podporuje. Výměna ventilu vyjde zhruba na €50 až €120 a řídicí deska je dražší, ale systémy CM a CVA stojí tolik, že oprava obvykle poráží výměnu — a pokus o restart je zdarma, takže stojí za to ho před volbou vyzkoušet. Kódy samotné si záložte: [stránka F10 a F17](https://cs.codefixcoffee.com/miele/cm-cva-machines/f10-f17/) a [stránka F77](https://cs.codefixcoffee.com/miele/cm-cva-machines/f77/) společně pokrývají závady, se kterými se jako majitel skutečně setkáte.

### Tip pro české podmínky

V mnoha regionech České republiky je voda z vodovodu středně tvrdá až tvrdá, takže kámen v přívodním ventilu i ucpaný filtr jsou reálnější hrozbou, než naznačují univerzální intervaly údržby — plánovaného odvápnění se u nás bojte méně a provádějte ho raději častěji. Vestavní systém CVA s připojením na vodovod a elektřinu smí instalovat a servisovat jen kvalifikovaný technik, což platí i pro případné přesouvání stroje při rekonstrukci kuchyně.
