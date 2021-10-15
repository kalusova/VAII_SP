# VAII_SP
Podmienky pre odovzdanie semestrálnej práce z predmetu VAII 2021 
Nutnou podmienkou pre absolvovanie predmetu Vývoj aplikácií pre internet a intranet (VAII) je vypracovanie semestrálnej práce. Podmienky, ktoré práca musí spĺňať, sú uvedené v nasledujúcom texte.

Kontrolné termíny
Počas semestra bude stav semestrálnej práce kontrolovaný na dvoch cvičeniach a to v 4. a 9. týždni (ak nenastane nič neočakávané). Na kontrolnom termíne bude vyučujúci iba kontrolovať stav semestrálnej práce podľa stanovených podmienok:

Termín 1 
- Použitie GIT, 
- Minimálne 3 rozdielne netriviálne statické HTML stránky
- Aspoň vlastných 10 CSS pravidiel (externe pripojené)
- Valídne HTML a CSS
- Responzívny dizajn

Termín 2
- Implementované všetky CRUD operácie
- Kontrola vstupov na strane klienta, aj servera
- Netriviálny JavaScript

Pre odovzdanie semestrálnej práce je nutné, aby študent získal z kontrolných termínov 12 a viac bodov.
Termíny
1.	Riadny termín odovzdania práce bude vopred oznámený a na ňom je možné získať 58 bodov. Termín býva zvyčajne v 1. polovici januára, ale prácu je možné odovzdať aj v priebehu cvičení v 12. týždni. 
2.	Náhradný termín bude cez skúškové obdobie (zvyčajne 2. polovica januára),  na tomto termíne je možné za semestrálnu prácu získať max. 48 bodov.

Povinné náležitosti semestrálnej práce
Semestrálna práca musí spĺňať nasledovné povinné podmienky. Ak niektoré z nich nie sú splnené, prácu nie je možné obhajovať. 
Ak máte špecifickú prácu, ktorá nespĺňa tieto požiadavky, ale je dostatočne zložitá v inom smere (napr. netriviálna hra v JS a pod.), je nutné sa vopred s vyučujúcimi dohodnúť, či je práca vhodná ako semestrálna.
Povinné požiadavky na semestrálnu prácu:
●	min. 5 dynamických stránok
●	min. 50 vlastných riadkov kódu v Javascripte (Typescript, Dart, ...)
●	min. 20 vlastných CSS pravidiel (mimo Bootstrap a pod.) 
●	min. 4 zmysluplné DB entity, všetky použité v aplikácii
●	v aplikácii sú implementované všetky CRUD (čítanie, vytváranie, úprava a mazanie dát) operácie nad hlavnou entitou a jednou ďalšou, ostatné entity musia mať implementované aspoň dve operácie. 
●	aplikácia musí obsahovať časť, do ktorej je nutné sa prihlásiť
Do počtu sa nerátajú prevzaté (napr. z cvičení alebo zbierky úloh z VAII) a mierne upravené, frameworkom/knižnicou vygenerované DB entity, stránky, CSS pravidlá, kód, atď.
Semestrálna práca 
1.	Každý študent vypracováva prácu samostatne a osobne ju aj obhajuje, pričom ju nie je možné odovzdať prostredníctvom iného študenta. Nesamostatné vypracovanie jednotlivých častí je dôvodom na neabsolvovanie predmetu.
2.	Jednu semestrálnu prácu môžu vypracovať aj viacerí študenti spoločne. Zložitosť takejto práce musí byť adekvátna počtu študentov, pričom každý študent pracuje na svojej časti, avšak musí spĺňať všetky podmienky na celú semestrálnu prácu. Rozdelenie práce medzi študentov musí byť jednoznačne stanovené.  
a.	Pred odovzdaním takejto práce je potrebné prebrať tému práce a jej rozdelenie s vyučujúcim, aby ste predišli jej neuznaniu, resp. neuznaniu jednotlivých častí.
b.	Pokiaľ je nejaká časť hodnotená ako slabá alebo nedostačujúca, bude za ňu strhnutý príslušný počet bodov. 
3.	Semestrálna práca musí byť webová aplikácia, ktorá využíva nejaké dynamické technológie na strane servera.
4.	Prácu je možné prezentovať na vlastnom počítači alebo notebooku, prípadne umiestniť na verejne dostupný webhosting. Zdrojové kódy práce musia byť pre hodnotiaceho dostupné cez GIT repozitár. Výnimku je potrebné sa dohodnúť s vyučujúcimi.
5.	Za prácu, ktorá je nad rámec popísaných požiadaviek (napr. použitie iných frameworkov alebo technológií, aké sú preberané na prednáškach), je možné získať bonusové body.
6.	Dokumentácia k práci je dobrovoľná.
7.	Práca sa obhajuje priamo pri odovzdávaní, kde študent obháji svoje riešenie semestrálnej práce. Študent musí mať prístup ku zdrojovým kódom aplikácie počas obhajoby práce, aby bolo možné overiť samostatnosť vypracovania.
8.	Ak práca používa kód, ktorého študent nie je autorom, je potrebné k tomuto kódu pripísať do komentára jeho zdroj.

Aplikácia
Výsledná internetová aplikácia je rozdelená na klientsku a serverovú časť, ktoré musia spĺňať nasledovné požiadavky:
Všeobecné požiadavky
1.	Zdrojový kód musí byť správne štruktúrovaný, členený a prehľadne formátovaný. Dôvodom na zrážku bodov je neprehľadný, zle členený alebo často sa opakujúci kód.
2.	Pri vytváraní by ste mali dodržiavať postupy objektovo orientovaného programovania (OOP) a používať MVC (prípadne iné architektúry ako MVVM, MVP, ...).
3.	Hodnotí sa kód, ktorý je vytvorený študentom. Pokiaľ je v aplikácii použitý framework, CMS alebo iné hotové riešenie bude hodnotená miera modifikácie alebo implementácie, ktorú študent sám vytvoril. V odovzdávanej aplikácií však musí byť v dostatočnej miere obsiahnutá aj vlastná tvorivá činnosť študenta. Ak chcete odovzdať semestrálnu prácu tohto typu, je vhodné svoj zámer vopred prekonzultovať s vyučujúcim.
4.	Aplikácia musí dodržať tieto zásady bezpečnosti:
a.	Kontrola vstupov, kontrolujúca nielen dátový typ, ale aj platnú hodnotu na strane servera aj klienta.
b.	Ošetrenie dopytov na DB voči útokom SQLInjection.
c.	Aplikácia musí obsahovať časť prístupnú až po prihlásení používateľa (t.j. musí obsahovať prihlasovací formulár).
d.	Heslá užívateľov musia byť bezpečne uložené, buď na úrovni databázy alebo aplikačnej logiky viď. problematika „password salted hash“.
5.	Klientska strana musí so stranou servera komunikovať asynchrónne (AJAX), min. dvoma spôsobmi z nasledujúceho zoznamu:
a.	odosielanie formulárov
b.	editovanie záznamu priamo v tabuľke (in-place editing)
c.	prihlasovanie do aplikácie
d.	filtrovanie záznamov tabuľke
e.	načítavanie obsahu tabuľky
f.	stránkovanie obsahu
g.	iné netriviálne volania, podľa vlastného výberu

 
Server – databáza 
1.	Musí obsahovať minimálne 4 samostatné entity (databázové tabuľky). Do počtu sa nezarátava asociačná tabuľka (dekompozícia vzťahu M:N) a frameworkom / knižnicou vygenerované tabuľky.
2.	Databáza by mala spĺňať normalizáciu; t.j. žiadne duplicity dát a nezmyselné tabuľky, ktoré sú vytvorené len do počtu. Príklady nevhodného použitia napr.:
a.	Pre každého užívateľa sa generuje vlastná tabuľka – stačí jedna tabuľka, užívateľov rozdeľuje ich ID atribút 
b.	Každá rola užívateľa má vlastnú tabuľku – do tabuľky užívateľov stačí pridať stĺpec, ktorý nesie informáciu o roliach
Server – aplikačná logika
1.	Aplikácia vykonáva nad DB všetky operácie – vkladanie, čítanie, mazanie a upravovanie dát.
2.	Aplikácia využíva všetky entity v DB. Nepoužívaná entita sa nezarátava do počtu.
Klient – aplikačná logika + GUI
1.	Aplikácia musí obsahovať minimálne 5 rôznych podstránok s dynamickým obsahom.
2.	Aplikácia musí mať responzívny dizajn, t.j. jej zobrazenie sa musí vhodne prispôsobiť rozlíšeniu displeja, na ktorom bude zobrazovaná.
3.	Vzhľad a formát aplikácie musí definovať minimálne 20 zmysluplných CSS pravidiel.
4.	Je potrebné vypracovať vlastný klientsky skript o veľkosti minimálne 50 riadkov. Skript musí byť zmysluplný a používaný v aplikácii.
5.	GUI musí spĺňať pokročilé funkcie pre správu dát v aplikácii. Zlé riešenie je napr. mazanie záznamu pri manuálnom zadaní ID riadku a pod.
6.	Aplikácia musí generovať výstupy podľa W3C štandardov – resp. študent musí zdôvodniť, prečo aplikácia nezodpovedá štandardom.
