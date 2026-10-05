---
title: Miele F77: kód poruchy inicializace ventilů
description: Kód F77 u kávovarů Miele CM a CVA značí vnitřní poruchu při inicializaci ventilů. Zkuste nejprve restart; pokud se F77 opakuje, je to práce pro servis.
---

Výrobci kávovarů Miele patří ke sdílnějším — významy kódů F, které plní vlastní autodiagnostika, najdete vytisknuté přímo v návodech k obsluze, dostupných i na [miele.com](https://www.miele.com). Právě F77 je ale kód, který potkat nechcete. Jde o zastřešující hlášení **vnitřní poruchy zjištěné při spuštění stroje**, v praxi téměř vždy spojené s ventilovým systémem, který se nepodařilo inicializovat, a v tabulce kódů Miele patří k nejtěžším položkám. Zobrazí se jak na volně stojících přístrojích CM (CM 5510, CM 6150), tak na vestavěných jednotkách CVA (CVA 6401, CVA 6805), jen znění se mezi oběma řadami mírně liší. [Kompletní stránka o chybě F77](https://cs.codefixcoffee.com/miele/cm-cva-machines/f77/) rozebírá opravu do hloubky; zde vysvětlíme, co inicializace vlastně znamená a kde přesně vede hranice domácí opravy.

## Co inicializace ve skutečnosti znamená

Po zapnutí se kávovar Miele nespokojí s tím, že by se jen zahřál a čekal. Řídicí elektronika pokaždé provede stroj startovní sekvencí a ověří, že vnitřní komponenty odpovídají očekávání, než vám nabídne první nápoj. Přesně v této fázi se F77 zapisuje: deska při inicializaci zaznamenala vnitřní poruchu a nejčastěji jde o ventily, které uvnitř přístroje rozvádějí vodu. Návod záměrně volí obecné znění („vnitřní porucha“), a proto jediné číslo může pokrývat vadu ventilu, čerpadla i řídicí desky.

Právě tato šířka F77 odlišuje od přátelštějších kódů. [F10 a F17](https://cs.codefixcoffee.com/miele/cm-cva-machines/f10-f17/) hlásí, že se stroj pokusil nasát vodu a neuspěl: prázdná, špatně vsazená nebo zaseknutá výsuvná nádrž u přístrojů CM, případně zavřený přívodní ventil či ucpaný filtr u trvale připojených CVA. Ty opravdu vyřešíte sami. F77 je naopak hodnoceno jako vážná porucha, u níž se vlastní oprava nedoporučuje — jediný lék, který manuál připouští, je restart.

## První krok: restart, který doporučuje samo Miele

I tak se vyplatí restart provést pořádně, než se pustíte do čehokoli jiného:

1. Stroj vypněte senzorem On/Off — pohotovostní režim se nepočítá.
2. Vytáhněte vidlici ze zásuvky.
3. Nechte přístroj odpojený několik minut. Vrátilo se F77 už dříve po krátkém vypnutí, vydržte celou hodinu — přesně to některé manuály Miele doporučují.
4. Zapojte stroj zpět a sledujte jedinou věc: objeví se porucha okamžitě během inicializace, nebo až později, když si objednáte nápoj?

Právě časování je to nejcennější, co můžete pozorovat. F77, které po restartu zmizí a už se nevrátí, bylo přechodné — a restart byl celou opravou. F77, které se vrací okamžitě, pokaždé na stejném místě startovní sekvence, svědčí o komponentě, která neprochází vlastní kontrolou, nikoli o jednorázovém zmatení desky. Než kohokoli zavoláte, poznamenejte si tento údaj.

## Kdy je ventil opravdu prací pro servis Miele

Nepomůže-li restart, reálnými příčinami jsou ventilový blok, čerpadlo nebo řídicí deska — a z této trojice je deska nejdražší. Správný postup tehdy zní: zastavit a stroj odevzdat.

- **Kryt neotevírejte.** Miele výslovně uvádí, že plášť nesmí být odstraňován: uvnitř přístroje zůstávají nebezpečná napětí i tlaková vodní soustava. Toto varování míří přesně na podobný typ poruchy.
- **Před telefonátem si zjistěte model.** CM 5510/6150 a CVA 6401/6805 se uvnitř liší a přesný typ výrazně zrychlí diagnózu.
- **Očekávejte cenu komponenty, ne záhadnou cenovku.** Ventilový blok stojí zhruba €50 až €120, řídicí deska výrazně více. Servis výrobce mimo záruku u superautomatu obvykle vyjde na €250 až €500 včetně zaslání a nezávislí opraváři espresso jsou u výměny jednoho dílu většinou levnější.

A právě tato cenová hranice je důvod, proč se F77 obvykle vyplatí opravit místo pořízení nového stroje: CM i CVA stojí tolik, že i horní konec servisní ceny dává smysl proti nové vestavěné jednotce — přičemž restart, který rozhodne, nic nestojí.

## F77 v kontextu zbytku tabulky

V celém [přehledu kódů Miele](https://cs.codefixcoffee.com/miele/) se drží stejný vzorec: kódy okolo přívodu vody patří k dřezu a vám, kódy ventilů a varné jednotky patří servisu a F77 je nejčistší ukázkou druhé skupiny. Máte-li na lavičce vedle něj stroj Sage nebo Breville, počítejte s úplně jiným systémem — jeho kódy vycházejí ze servisní tabulky, kterou výrobce nezveřejňuje vůbec, a rozplétá ji náš [průvodce Breville a Sage](https://cs.codefixcoffee.com/breville/).

### Rada z českého prostředí

Vodovodní voda je ve většině České republiky středně tvrdá až tvrdá, takže vodní cesty kávovarů Miele se tady zanášejí rychleji než v měkkých regionech. Odvápnění proto provádějte pečlivě a včas — šetří ventily, čerpadlo i varnou jednotku a snižuje riziko dalších vodních poruch. Autorizovaný servis Miele v ČR funguje, takže se u opakovaného F77 nemusíte obávat posílání přístroje do zahraničí; vystačíte si s přesným popisem fáze, v níž se kód objevuje.
