---
title: Kamínky v kávě — kódy mlýnku a poškozené frézy
description: Kamínek z kávy zasekne frézy a Jura hlásí chybu 12, De'Longhi kód 1454. Odkud se v zrní berou kamínky, jak mlýnek prověřit a kdy měnit frézy.
---

Každý plnoautomatický kávovar má ve mlýnku nepřítele, na kterého chybové menu nikdy nepoukáže: malý kamínek, který cestuje se syrovou kávou přímo z plantáže. Dva kódy od dvou různých značek se k němu ale vztahují. U Jury je to [chyba 12](https://cs.codefixcoffee.com/jura/automatic-machines/error-12/), tedy hlášení, že se mlýnek nespustil. U De'Longhi jde o zaseknutý mlýnek, který [novější modely zapisují pod kódem 1454](https://cs.codefixcoffee.com/delonghi/magnifica-dinamica/grinder-stuck-code-1454/). Elektronika je odlišná, kamínek pořád stejný.

## Dva kódy, jedna příčina

Chyba 12 u Jury znamená, že řídicí deska nařídila mletí, ale mlýnek se vůbec neroztáčel: motor je zadřený nebo frézy blokuje cizí předmět, a v drtivé většině případů jde o kamínek nasávaný spolu se zrním. De'Longhi má k tomu ekvivalent v podobě zastaveného motoru mlýnku kvůli kamenu, silně olejnaté vrstvě zrní nebo natlačené mleté kávě pod frézami. De'Longhi většinou na displeji zobrazuje slova, nikoli čísla, takže „1454" možná nikdy neuvidíte — ale přesně to číslo si vede servisní menu.

## Proč kamínky zaseknou frézy

Kávové třešně se v zemích původu suší na dvorech a zvýšených roštech a do zrní se přitom dostanou kamínky, hroudy hlíny i prach. Pražírny kávu prosívají a třídí, kámen podobný praženému zrnu velikostí i váhou ale občas projde a při vytřídění nevyplave spolu s vadnými zrny.

Problém je pak čistě geometrický. Při jemnosti na espresso se mezera mezi frézami pohybuje v zlomcích milimetru. Zrno se v ní rozřeže, kamínek ne — zaklíní se, motor se o něj zastaví a deska vyhlásí kód. Olejnatá tmavá pražení dokáží způsobit stejné zastavení pomalejší cestou: oleje a jemné částice se pod frézami slepují, dokud není komora pevně ucpaná.

### GIGA a otázka, který mlýnek

Dvoumlýnkové Jura GIGA má levý a pravý mlýnek a chyba 12 jmenuje konkrétně **levý mlýnek** — to se hodí, protože hned víte, který zásobník vysypat a které hrdlo vysát. Servisní podklady ale přidávají výhradu: u GIGA 6 může totéž číslo namísto kamene signalizovat komunikační nebo senzorickou závadu, kterou jako první krok řeší restart. Odpojte tedy přístroj ze sítě, spusťte jej znovu a teprve pokud kód přetrvá, pokračujte jako po kamínku.

## Prověření krok za krokem

Než usoudíte, že je něco rozbité, projděte body v tomto pořadí.

1. Odpojte kávovar na pět minut od napájení a restartujte jej — u GIGA 6 tím vyřadíte komunikační variantu chyby 12.
2. Zásobník na zrno zcela vyprázdněte a zrno z jeho dna prohlédněte. Hledejte kamínky nebo slepené hrudky olejnatého pražení; kávu nechte projít mezi prsty, pouhý pohled nestačí.
3. Vývod zásobníku a hrdlo mlýnku vysajte úzkou hubicí. **Do fréz nikdy nesahejte ničím kovovým** — šroubovák odlomí ostří, které se snažíte zachránit.
4. U De'Longhi přetočte regulátor jemnosti na nejhrubší stupeň a zpět; tentokrát to jednou vydržte i při vypnutém mlýnku. Standardně platí, že se regulátor smí otáčet jen za běhu mlýnku — proto existuje zpráva „[kávu máte pomletou příliš jemně, seřiďte mlýnek](https://cs.codefixcoffee.com/delonghi/magnifica-dinamica/ground-too-fine-adjust-mill/)".
5. Vyprázdněte nádobu na sedlinu i vaničku, obě nasaďte zpět a kávovar restartujte, aby se uvedl do výchozí polohy. Vyzkoušejte malou hrst zrní, ne plný zásobník.

Dvě upozornění na závěr. Nenechte mlýnek opakovaně nabíhat proti zaseknutí — motor se přehřívá a z odstranitelné ucpanosti se stane mrtvý motor. A pokud mlýnek při čistém hrdle bzučí, ale neotáčí se, jeví se to jinak: u Jury znamená zaseknutý motor a nutnou výměnu, u De'Longhi bývá kámen zaklíněný pod horní frézou a servis jej vyjme a uvolní.

## Jak odlišit kámen od jiných závad mlýnku

Ne každé zastavení mlýnku způsobuje kámen. [Chyba 01 u Philips](https://cs.codefixcoffee.com/philips-saeco/espresso-machines/error-01/) znamená zutučenou mletou kávu v tryse mezi mlýnkem a varnou jednotkou — následek olejnatého zrna pomletého příliš jemně — a odstraňuje se rukojetí lžíce a vysavačem, tedy bez operace. A de'longhi hlášení o příliš jemném mletí závadu mlýnku vůbec nehlásí: jde o tlak při přípravě a u strojů starších zhruba roku bývá skutečným řešením odvápnění, ne regulátor. Údržbové návody pro stroje Philips/Saeco najdete i v [oficiální podpoře Philips](https://www.philips.com).

## Kdy jsou frézy opravdu poškozené

Pokud kávovar s kamenem nějakou dobu běžel, mohou být ostří fréz vyštípnutá. Znaky poté: náhle hlučnější mlýnek, kolísající hrubost mletí a viditelné zářezy na zubech fréz při prohlídce se světlem. Frézy se vyměňují: sada fréz stojí zhruba 25–45 €, motor mlýnku Jura 60–140 € a sestava mlýnku De'Longhi 60–100 €. U GIGA ale výměna fréz i motoru vyžaduje rozsáhlou demontáž — je to oprava pro dílnu, pokud už tyto stroje pravidelně servisujete. Obecně se vyplatí u řad GIGA a Z; u deset let starého stroje vstupní třídy si nechte nejprve spočítat rozpočet. Kontakty na autorizované servisy najdete na [oficiálních stránkách Jura](https://www.jura.com).

Prevence je nenápadná, ale účinná: před každým doplněním zrna věnujte zrní dvousekundový pohled a u nevytříděných šarží či doma pražené kávy buďte dvojnásob obezřetní. Kompletní přehledy kódů — od termobloku přes ventil a varnou jednotku až po mlýnek — najdete v rejstřících [Jura](https://cs.codefixcoffee.com/jura/) a [De'Longhi](https://cs.codefixcoffee.com/delonghi/).

### Tipy pro české podmínky

Zrní od tuzemských mikropražíren i z běžného maloobchodu bývá dobře vytříděné; riziko kamínků spočívá hlavně v levných nevytříděných partiích z výprodejů a v domácím pražení. Pokud si kávu pražíte sami, přeberte zelené zrno před pražením na rovném podkladě — kamínek poznáte už podle vyšší hmotnosti. Náhradní sady fréz na rozšířené modely se dají sehnat u specializovaných prodejců dílů na kávovary, takže i starší stroj často stojí za opravu.
