# Kontext - zadání tutoriálu

Tak potřebuju dát dohromady tutoriál o tom, jak úplně od začátku zaznamenáváme know how, ideu, koncept, specifikace a další věci. Musí to být udělané jako prezentace, kde vlastně krok po kroku vysvětlíme, co děláme, proč to děláme a na začátku musíme i říct, co je cílem tady toho celého.

Naučíme se trošku pracovat s MDéčkama, protože je i velice super si posílat MDéčka mezi sebou, když třeba na něčem pracuješ, na nějakém nápadu.

## Krok 1: Zaznamenání nápadu

Jako první chci dát to, že zaznačíš nějaký svůj nápad. To znamená, nejprve tam dáš prompt, který se tě na spoustu věcí doptá. To znamená, že jako první musíš vymyslet prompt, který se tě doptá, co chceš dělat, co to je, co to není. Z tebe povytahuje základní esence tvého nápadu.

Ten brainstorming trvá tak dlouho, dokud to není dostatečně robustní, a potom z toho vyrobí MDéčko, které se jmenuje **idea.md**. To je zaznačení celkového nápadu. V ideálním případě by bylo dobré to i nějakým způsobem verzovat, jo, protože se k tomu budeš vracet a buď se to aktualizuje, ať v tom je nějakej pořádek.

## Krok 2: Know-how

Postup je, že začneš zaznačovat know how. Může to být:
- know how, které víš o daném projektu
- potřebná data, ze kterých čerpáš
- z rozhovoru s experty
- z literatury nebo článků
- různé frameworky
- něco, co chceš, aby ten model ctěl jako know how projektu
- nějaká tvoje velice osobní záležitost, kterou do toho projektu vkládáš, ale on se o to pořád opírá

**Příklad:** Když spočítáš cenu rekonstrukce bytu, tak know how je, že víš, co všechno se musí udělat, kde se lidé často spalují. Když tvoříš televizní pořad, zase zohledňuješ spoustu věcí, co normálně lidé bez praxe nemají k dispozici.

File pojmenuješ **know-how.md**.

## Krok 3: Zapojení dalších lidí (Ping-pong MD souborů)

Pokud chceš zainteresovat někoho dalšího, vezmeš tyhle dva soubory, strčíš si je dovnitř a poprosíš Clauda, ať ti vygeneruje otázky pro toho druhého člověka plus celej kontext, ale **nezaznačí tam celé know-how**. Důležité jsou jenom ty nápady, co potřebuješ vědět - ať si ten člověk základy nablíkuje, ale hlavně tam je to, co po něm potřebuješ.

Ten člověk to nakrmí svému jazykovému modelu, model ho tím detailně provede a on potom ti pošle zpátky MD soubory.

Tj. posíláš ven **questions-1.md** a on ti pošle **answers-1.md**. V druhém kole jsou to **questions-2.md** a **answers-2.md** atd.

Když zapracováváš jeho nápady, můžeš si to dát do separátního souboru: **external-know-how.md** nebo **external-ideas.md**, ať to neinfikuje tvoje základní elementy.

## Krok 4: První kompilace

Řekneš Claudeovi v Coworku, ať ti vyrobí složku **01-prvni-kompilace** a dovnitř už začneš dělat nové MD - první koncept toho, jak by to mohlo vypadat. Tam vlastně kloubíš dohromady externí know-how, ideje a interní ty tvoje. Soubor se jmenuje například **koncept-1.md** a je popsaný velice detailně, co bys chtěl dělat, jak by to mělo vypadat.

## Krok 5: Specifikace

Potom uděláš další složku **specifikace** - to už musí být vyloženě technické. Na základě detailních zadání se vyrobí specifikace:
- jak se to musí natáčet
- jaká technologie kde bude použita
- cokoliv zabere času
- jak bude zhruba cena
- realizační specifikace

Ideálně iteruješ a tu specifikaci děláte spolu s modelem - vznikne něco hodně robustního a najednou máš i náročnost práce zaznačenou v dalším MD souboru.

## Důležité poznámky

- Tohle se dělá v **Claude Desktop v Coworku**
- Vždycky si někde vyrobíš nějakou složku
- Řekneš Claudeovi, v jaké složce má být a následně tam vyrábí MD a další složky
- MD soubory ve výsledku **nepíšeš ty**, ale vždycky na konci celé iterační session, kdy s tím přemýšlíš, mu řekneš: „Ano, tak teďka z toho vyrob toto MD."
- To je vlastně zaznačení té esence myšlenek, které jste právě probrali

## Cíl prezentace

- Pro netechnického člověka (tátu)
- Krok za krokem
- Vysvětlit PROČ to děláme
- Ukázat struktury jak to vypadá
- HTML prezentace s animacemi
- U každého slidu příklad: televizní pořad o AI
- Ukázat reálný chat, MD soubor, ping-pong komunikaci
- Struktura složky vizualizovaná jako Mac Finder
- Hodně ilustrací, méně textu
- Interaktivní, zábavné, edukační
