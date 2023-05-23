# Answers for Fuzzy Systems Exam - 2023

- ## 1. Definícia fuzzy množiny a charakteristiky popisujúce funkciu príslušnosti.

**Fuzzy množina je matematický koncept, ktorý rozširuje tradičnú teóriu množín o možnosť priradiť prvkom množiny stupne príslušnosti. Tieto stupne príslušnosti sú reprezentované hodnotami v intervale medzi 0 a 1, pričom hodnota 0 znamená úplnú nepripradivosť prvku do množiny a hodnota 1 znamená úplnú príslušnosť prvku do množiny.**

Charakteristiky popisujúce funkciu príslušnosti určujú, ako je priradený stupeň príslušnosti jednotlivým prvkom množiny. Existuje niekoľko typických charakteristík funkcií príslušnosti, ktoré sa používajú pri modelovaní fuzzy množín. Niektoré z týchto charakteristík zahŕňajú:

![image](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/b2f8aba0-37d4-449d-b110-29ab3fee0765)
![image](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/bea870ad-40b1-4ee2-804a-c7de780e6a6f)

1. **Trojuholníková charakteristika**: Táto charakteristika je definovaná pomocou trojuholníka a je často používaná pri aproximácii ostrých hraníc množiny.

2. **Trapezová charakteristika**: Táto charakteristika je podobná trojuholníkovej charakteristike, ale používa sa na modelovanie širších oblastí množiny s postupným prechodom medzi príslušnosťou a nepripradivosťou.

3. **Gaussovská charakteristika**: Táto charakteristika je definovaná pomocou gaussovej krivky a je často používaná pri modelovaní rozmazaných, rozptýlených hodnôt v množine.

4. **Singleton charakteristika**: Táto charakteristika priradzuje stupeň príslušnosti hodnote 1 iba v prípade, že prvok množiny je rovnaký ako konkrétna hodnota.

5. **Iné charakteristiky**: Okrem vyššie uvedených charakteristík existuje mnoho ďalších charakteristík, ktoré sa používajú na modelovanie rôznych typov fuzzy množín, napríklad sigmoidná, kosiarková, S-charakteristika atď.

Tieto charakteristiky popisujúce funkciu príslušnosti určujú, ako sa hodnoty prvkov priradzujú k fuzzy množine a akým spôsobom je určovaný stupeň príslušnosti jednotlivých prvkov do množiny.

____

- ## 2. Definícia lingvistickej premennej a jej základné vlastnosti a význam.

**Lingvistická premenná je koncept v oblasti fuzzy logiky a fuzzy množín, ktorý umožňuje reprezentovať a manipulovať s lingvistickými hodnotami. Lingvistická premenná slúži na vyjadrenie nejasnosti a vaguity v rámci informácií a umožňuje modelovať a analyzovať ľudské jazykové koncepty.**

Hlavnými vlastnosťami lingvistickej premennej sú:

![Lectures - 2023_Страница_016](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/ccd2d19f-2efb-4ca4-92da-6414815bba0e)

1. **Univerzum**: Univerzum je súbor všetkých možných hodnôt, ktoré lingvistická premenná môže nadobudnúť. Napríklad, ak hovoríme o premenných ako "teplota" alebo "rýchlosť", univerzum by mohlo byť definované ako interval reálnych čísel.

2. **Príslušnosť**: Každá hodnota v univerze je priradená k niektorej lingvistickej množine. Príslušnosť určuje, do akej miery daná hodnota patrí do danej množiny. Príslušnosť môže byť vyjadrená ako číselný stupeň v intervale medzi 0 a 1.

3. **Lingvistické termíny**: Lingvistická premenná obsahuje lingvistické termíny, ktoré predstavujú rôzne kategórie alebo hodnoty v rámci danej premennej. Tieto termíny sú definované pomocou funkcií príslušnosti, ktoré určujú, ako sa hodnoty priradzujú k jednotlivým termínom.

**Lingvistické premenné majú veľký význam v oblasti umelého inteligentného spracovania a rozhodovania, pretože umožňujú modelovať a pracovať s ľudskými konceptmi a jazykom.** Tieto premenné nám umožňujú zahrnúť nejasnosti a vaguity do procesu rozhodovania a logického vyhodnocovania, čo je veľmi užitočné pri riešení problémov v prostredí s neistotou a nejasnosťou.

____

- ## 3. Operácie s fuzzy množinami – základné delenie a ich definície.

**Operácie s fuzzy množinami sa používajú na manipuláciu a kombinovanie hodnôt fuzzy množín.**
![Lectures - 2023_Страница_018](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/45bc99b4-fba8-4f8b-b9c4-3c18210be23c)

Tu sú základné operácie a ich definície:

1. **Unárna komplementárna operácia**:
Unárny komplement fuzzy množiny A je definovaný ako fuzzy množina ďalších hodnôt, ktoré vyjadrujú nepripradivosť prvkov množiny A. Pre každý prvok x z univerza je hodnota príslušnosti komplementárnej množiny získaná ako 1 mínus hodnota príslušnosti prvku x v množine A.

2. **Binárna operácia zjednotenie**:
Binárne zjednotenie fuzzy množín A a B je definované ako fuzzy množina, ktorá obsahuje všetky hodnoty z oboch množín s maximálnymi hodnotami príslušnosti pre každý prvok. Pre každý prvok x z univerza je hodnota príslušnosti výslednej množiny získaná ako maximum z hodnôt príslušnosti prvku x v množinách A a B.

3. **Binárna operácia prienik**:
Binárny prienik fuzzy množín A a B je definovaný ako fuzzy množina, ktorá obsahuje iba hodnoty, ktoré sú spoločné pre obe množiny s minimálnymi hodnotami príslušnosti pre každý prvok. Pre každý prvok x z univerza je hodnota príslušnosti výslednej množiny získaná ako minimum z hodnôt príslušnosti prvku x v množinách A a B.

4. **Binárna operácia rozdiel**:
Binárny rozdiel fuzzy množín A a B je definovaný ako fuzzy množina, ktorá obsahuje hodnoty z množiny A s minimálnymi hodnotami príslušnosti prvkov z množiny B. Pre každý prvok x z univerza je hodnota príslušnosti výslednej množiny získaná ako minimum z hodnoty príslušnosti prvku x v množine A a hodnoty 1 mínus hodnota príslušnosti prvku x v množine B.

5. **Binárna operácia súčin**:
Binárny súčin fuzzy množín A a B je definovaný ako fuzzy množina, ktorá obsahuje hodnoty, ktoré sú súčasne prítomné v oboch množinách. Pre každý prvok x z univerza je hodnota príslušnosti výslednej množiny získaná ako súčin hodnoty príslušnosti prvku x v množine A a hodnoty príslušnosti

____

- ## 4. Typy t-noriem a t-konoriem, ich charakteristika, príklady reprezentantov a prísnosť (tolerantnosť) operátorov.

T-normy a T-konormy sú dôležitými operátormi v teórii fuzzy množín, ktoré sa používajú na kombináciu a zlučovanie hodnôt príslušnosti.
![Lectures - 2023_Страница_022](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/e280b610-6ca9-4c87-bfba-e353a88252f7)
![Lectures - 2023_Страница_023](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/ce65636e-9c5d-4e8e-a0c5-82f3c50dfc90)
![Lectures - 2023_Страница_024](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/4878821b-0c2a-4a34-8df2-4564ba019474)
![Lectures - 2023_Страница_025](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/e3fd0c91-d26e-49e5-8db0-786845af6c1c)
![Lectures - 2023_Страница_028](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/226a85c5-72cf-467d-a789-24e08b0068ea)
![Lectures - 2023_Страница_029](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/cae2e424-c264-43c0-86f3-6f8aa7031b68)

**T-norma (t-norm) je binárny operátor, ktorý kombinuje dve hodnoty príslušnosti a generuje výslednú hodnotu príslušnosti**. Niektoré typické t-normy sú:

1. **Minimum (MIN)**: T-norma získava hodnotu príslušnosti ako minimum z dvoch hodnôt príslušnosti. Táto t-norma reprezentuje najmenší spoločný stupeň príslušnosti.

2. **Produkt (PROD)**: T-norma získava hodnotu príslušnosti ako súčin dvoch hodnôt príslušnosti. Táto t-norma je obzvlášť užitočná pri kombinácii pravdepodobností.

**T-konorma (t-conorm) je tiež binárny operátor, ktorý kombinuje dve hodnoty príslušnosti a generuje výslednú hodnotu príslušnosti**. Niektoré typické t-konormy sú:

1. **Maximálny (MAX)**: T-konorma získava hodnotu príslušnosti ako maximum z dvoch hodnôt príslušnosti. Táto t-konorma reprezentuje najväčší spoločný stupeň príslušnosti.

2. **Súčet (SUM)**: T-konorma získava hodnotu príslušnosti ako súčet dvoch hodnôt príslušnosti. Táto t-konorma je často používaná pri agregácii neurčitých informácií.

Príklady reprezentantov t-normy a t-konormy môžu byť:

- Minimum (MIN): Ak máme hodnoty príslušnosti A = 0,6 a B = 0,4, t-norma MIN vráti výsledok 0,4.

- Produkt (PROD): Ak máme hodnoty príslušnosti A = 0,6 a B = 0,4, t-norma PROD vráti výsledok 0,24.

- Maximálny (MAX): Ak máme hodnoty príslušnosti A = 0,6 a B = 0,4, t-konorma MAX vráti výsledok 0,6.

- Súčet (SUM): Ak máme hodnoty príslušnosti A = 0,6 a B = 0,4, t-konorma SUM vráti výsledok 1.

**Prísnosť (tolerantnosť) operátorov je ich schopnosť zachovať informácie pri kombinácii hodnôt príslušnosti.** T-normy sú prísnejšie (menej tolerantné) ako t-konormy, pretože výsledná hodnota príslušnosti je obmedzená maximálnou hodnotou jednej z kombinovaných hodnôt. Naopak, t-konormy sú menej prísne (viac tolerantné), pretože výsledná hodnota príslušnosti môže byť vyššia ako vstupné hodnoty príslušnosti.
____

- ## 5. Popíšte vzťah expertného systému a fuzzy regulátora a jeho základnú štruktúru.

### ES
An expert system is made up of three parts:

**Komunikačny modul** - Toto je systém, ktorý umožňuje neodbornému používateľovi vkladať otázky expertnému systému a dostávať rady. Užívateľské rozhranie je navrhnuté tak, aby bolo čo najjednoduchšie na používanie.

**Báza znalostí** - Toto je zbierka faktov a pravidiel. Báza znalostí je vytvorená z informácií poskytnutých ľudskými odborníkmi.

**Inferenčny mechanizmus** - Toto funguje podobne ako vyhľadávací engine, skúma bázu znalostí pre informácie, ktoré zodpovedajú otázke používateľa.
![Lectures - 2023_Страница_030](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/f2d2b10e-2e6e-482f-9252-d953b54552b4)

### FR

**Fuzzifikátor** - Úlohou fuzzifikátora je prevádzať ostre definované vstupné hodnoty na fuzzy hodnoty.

**Fuzzy znalostná báza (BZ)** - Ukladá informácie o všetkých vzťahoch medzi vstupno-výstupnými fuzzy premennými. Obsahuje tiež príslušnostné funkcie, ktoré definujú vstupné premenné pre fuzzy pravidlá a výstupné premenné pre riadený systém.

**Fuzzy pravidlová báza ?** - Ukladá informácie o fungovaní procesu v danom doméne.

**Inferenčný mechanizmus**: Mechanizmus, ktorý vyvodzuje výstupné akcie na základe vstupných podmienok a fuzzy pravidiel. Tento mechanizmus kombinuje informácie z rôznych pravidiel a generuje výstupnú hodnotu príslušnosti pre každú výstupnú premennú.

**Defuzzifikátor** - Úlohou defuzzifikátora je prevádzať fuzzy hodnoty získané z odvozovacieho enginu na ostre definované hodnoty.
![Lectures - 2023_Страница_032](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/a3582343-8b73-4564-b178-efaf8fd49f73)

Expertný systém je softvérový systém, ktorý simuluje a modeluje rozhodovanie ľudských expertov v konkrétnej oblasti. Je založený na znalostiach, skúsenostiach a pravidlách od odborníkov, ktoré sú reprezentované v podobe bázy znalostí. Expertný systém používa tieto znalosti na analýzu a vyhodnotenie problémov, generovanie odporúčaní a rozhodnutí v danom odbornom dome.

Fuzzy regulátor je systém, ktorý využíva princípy fuzzy logiky a fuzzy množín na riadenie a reguláciu dynamických systémov. Fuzzy regulátor využíva fuzzy pravidlá a inferenčný mechanizmus na generovanie výstupných akcií na základe vstupných podmienok a cieľového správania systému. Používa sa najmä v prípadoch, keď je modelovanie systému ťažké alebo výstupné akcie sú ťažko definovateľné pomocou tradičných presných metód.

Základná štruktúra fuzzy regulátora zahŕňa nasledujúce komponenty:

1. **Fuzzy množiny**: Definícia vstupných premenných a výstupných premenných pomocou fuzzy množín. Fuzzy množiny popisujú nejasnosti a neurčitosti v hodnotách premenných.

2. **Fuzzy pravidlá**: Sada pravidiel, ktoré pripájajú vstupné podmienky k výstupným akciám. Tieto pravidlá sú definované pomocou lingvistických premenných a logických vzťahov medzi nimi.

3. **Inferenčný mechanizmus**: Mechanizmus, ktorý vyvodzuje výstupné akcie na základe vstupných podmienok a fuzzy pravidiel. Tento mechanizmus kombinuje informácie z rôznych pravidiel a generuje výstupnú hodnotu príslušnosti pre každú výstupnú premennú.

4. **Defuzzyfikácia**: Proces konverzie výstupných hodnôt príslušnosti na konkrétne výstupné hodnoty, ktoré sú použiteľné pre riadený systém.

Vzťah medzi expertným systémom a fuzzy regulátorom spočíva v tom, že expertný systém môže poskytovať znalosti a pravidlá pre fuzzy regulátor. **Expertný systém môže byť použitý na vytvorenie bázy znalostí a pravidiel, ktoré sa následne používajú v fuzzy regulátore na riadenie systému. Expertný systém môže tiež poskytnúť spätnú väzbu a aktualizáciu znalostí a pravidiel v fuzzy regulátore na základe skúseností a výsledkov riadenia.**

____

- ## 6. Popíšte postup vyhodnocovania fuzzy pravidiel.
![Lectures - 2023_Страница_042](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/aae27bef-ae79-40c7-ad77-d34661afc7ea)
![Lectures - 2023_Страница_036](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/c533b117-fc53-4a9f-8502-86d51fe49019)
![Lectures - 2023_Страница_037](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/5f28ce31-3745-44cd-b423-7292522f9f87)

Postup vyhodnocovania fuzzy pravidiel v fuzzy systéme pozostáva z niekoľkých krokov:

1. **Fuzzifikácia vstupov**: Vstupné hodnoty sú konvertované do tvaru fuzzy množín pomocou príslušných funkcií príslušnosti. Tieto funkcie príslušnosti určujú, do akej miery daná hodnota patrí do jednotlivých fuzzy množín.

2. **Porovnanie fuzzy pravidiel**: Každé fuzzy pravidlo obsahuje vstupné podmienky a výstupnú akciu. Vyhodnocuje sa pravdivosť (spĺňanie) každého fuzzy pravidla na základe hodnôt príslušnosti vstupných podmienok. Používa sa t-norma (napr. minimum) na kombináciu hodnôt príslušnosti vstupných podmienok.

3. **Inferencia**: Vyhodnocuje sa, aká je hodnota pravdivosti (spĺňanie) každého fuzzy pravidla. Táto hodnota pravdivosti sa používa na priraďovanie váh výstupným akciám príslušných pravidiel. Váhy môžu byť napríklad hodnoty príslušnosti výstupných akcií alebo fixné hodnoty definované pre každé pravidlo.

4. **Agregácia výstupov**: Výstupné akcie príslušných pravidiel sa kombinujú pomocou t-konormy (napr. maximálneho operátoru) na získanie výsledných hodnôt príslušnosti pre každú výstupnú premennú. Tieto hodnoty príslušnosti reprezentujú výstupné fuzzy množiny.

5. **Defuzzifikácia**: Výsledné hodnoty príslušnosti sa konvertujú späť na konkrétne hodnoty pomocou defuzzifikačných metód. Tieto metódy môžu byť napríklad ťažisková metóda, stredová metóda alebo vážený priemer.

6. **Výstup**: Výsledné konkrétne hodnoty sú použité ako výstup fuzzy systému pre ďalšie spracovanie alebo akcie riadeného systému.

Tento postup vyhodnocovania fuzzy pravidiel je základným mechanizmom v fuzzy logike a fuzzy systémoch a umožňuje riešiť problémy s neistotou a neurčitosťou.

____

- ## 7. Popíšte úlohu fuzzifikácie a defuzzifikácie a uveďte základné metódy.
![Lectures - 2023_Страница_041](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/3a898b9f-c33d-4f8e-a817-eced5ad3b167)
![Lectures - 2023_Страница_044](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/d79bc1a0-c8cf-43e7-b5f1-2d21900a2a7b)
![Lectures - 2023_Страница_045](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/6221ff6e-809c-48ac-9366-c4a528a170ac)
![Lectures - 2023_Страница_046](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/71593691-936c-4a88-896e-96f2b27d6d03)

Fuzzifikácia a defuzzifikácia sú dva dôležité procesy v rámci operácií s fuzzy množinami. Obe tieto operácie sú nevyhnutné pre prevod medzi konkrétnymi hodnotami a fuzzy hodnotami príslušnosti.

1. **Fuzzifikácia**: Fuzzifikácia je proces konverzie konkrétnych hodnôt na hodnoty príslušnosti v rámci fuzzy množín. Je to proces mapovania vstupných hodnôt do tvaru fuzzy množín. Tento proces zohľadňuje neurčitosť a nejasnosti v hodnotách a reprezentuje ich pomocou funkcií príslušnosti.

Základné metódy fuzzifikácie zahŕňajú:

- **Trojuholníková funkcia príslušnosti**: Vstupná hodnota je mapovaná na trojuholníkovú fuzzy množinu, kde maximálna hodnota príslušnosti je dosiahnutá na vrchole trojuholníka a hodnota príslušnosti sa lineárne mení smerom od vrcholu.

- **Lichoběžníková funkcia príslušnosti**: Vstupná hodnota je mapovaná na lichoběžníkovú fuzzy množinu, kde maximálna hodnota príslušnosti je dosiahnutá v určenom intervale a hodnota príslušnosti je konštantná v tomto intervale.

- **Gaussovská funkcia príslušnosti**: Vstupná hodnota je mapovaná na gaussovskú funkciu príslušnosti, ktorá je charakterizovaná gaussovským tvarom krivky a reprezentuje postupné stúpanie a klesanie hodnoty príslušnosti okolo stredného bodu.

2. **Defuzzifikácia**: Defuzzifikácia je opačný proces fuzzifikácie, ktorý konvertuje fuzzy hodnoty príslušnosti na konkrétne hodnoty. Je to proces mapovania hodnôt príslušnosti na konkrétne hodnoty, aby sa získali jednoznačné výstupné hodnoty.

Základné metódy defuzzifikácie zahŕňajú:

- **Ťažisková metóda**: Táto metóda určuje stredovú hodnotu fuzzy množiny tým, že vypočíta ťažisko (stredový bod) krivky funkcie príslušnosti a použije ho ako výslednú hodnotu.

- **Stredová metóda**: Táto metóda určuje stredovú hodnotu fuzzy množiny ako priemernú hodnotu koncových bodov fuzzy množiny.

- **Vážený priemer**: Táto metóda kombinuje viacero výsledných hodnôt fuzzy množín pomocou váh a vypočíta vážený priemer ako výslednú hodnotu.

Tieto metódy fuzzifikácie a defuzzifikácie umožňujú prevod medzi konkrétnymi hodnotami a fuzzy hodnotami príslušnosti a sú dôležité pri operáciách s fuzzy množinami a fuzzy logikou.

____

- ## 8. Kritériá hodnotenia defuzzifikačných metód.
![Lectures - 2023_Страница_048](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/3688364f-7f96-4861-a4d4-37d0d48dff15)
![Lectures - 2023_Страница_049](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/becb900a-a3dd-43ac-a626-bd917124f125)
![Lectures - 2023_Страница_050](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/061055df-5f90-4563-aed0-651af6ad314d)
![Lectures - 2023_Страница_051](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/f8c7ce2d-8782-46fa-abd6-69f7573924de)

Pri hodnotení defuzzifikačných metód sa zvyčajne berú do úvahy nasledujúce kritériá:

1. **Spojitosť (Continuity)**: Toto kritérium zohľadňuje, do akej miery je výsledná hodnota defuzzifikácie spojitá. Vyššia hodnota kontinuity naznačuje hladšie prechody a menej "skokov" medzi hodnotami.

2. **Jednoznačnosť (Unambiguity)**: Toto kritérium sa týka jednoznačnosti a rozlišovacej schopnosti výslednej hodnoty defuzzifikácie. Vyššia hodnota jednoznačnosti naznačuje, že každej hodnote príslušnosti zodpovedá jednoznačná konkrétna hodnota.

3. **Prijateľnososť (Plausibility)**: Toto kritérium sa zaoberá prijateľnosťou výslednej hodnoty defuzzifikácie z hľadiska očakávaných vlastností systému. Prijateľná hodnota defuzzifikácie by mala zodpovedať logike a očakávaniam danej aplikácie.

4. **Výpočtová náročnosť**: Toto kritérium sa týka náročnosti výpočtových operácií pri použití danej metódy defuzzifikácie. Niektoré metódy môžu vyžadovať zložitejšie výpočty a vyššiu výpočtovú záťaž.

5. **Zohladňovanie prekrytí (Weight Counting)**: Toto kritérium sa týka berúc do úvahy váhy príslušnosti v jednotlivých hodnotách pri defuzzifikácii. Metóda by mala správne zohľadňovať a priradiť vhodné váhy jednotlivým hodnotám príslušnosti.

Pri výbere metódy defuzzifikácie je dôležité zvážiť tieto kritériá a zvoliť metódu, ktorá najlepšie vyhovuje požiadavkám konkrétnej aplikácie a očakávaniam výsledkov. Každá metóda má svoje výhody a obmedzenia, a preto je dôležité zvážiť ich v kontexte daného problému.

____

- ## 9. Základné delenie fuzzy regulátorov a ich stručná charakteristika.
![Lectures - 2023_Страница_053](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/3c741e73-1b5b-4b80-9c52-1c31dc03ca57)
![Lectures - 2023_Страница_054](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/defefec5-be20-4ba5-96af-ac17719a3e70)
![Lectures - 2023_Страница_055](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/c1d3f753-107c-445e-a9f5-5a16f722a206)


Fuzzy regulátory môžeme základne rozdeliť na nasledujúce typy:

1. **Mamdaniho fuzzy regulátory**:
- Charakteristika: Tento typ regulátora je založený na Mamdaniho metóde a využíva pravidlá typu "IF-THEN". Výstupné akcie sú reprezentované fuzzy množinami, ktoré sú kombinované pomocou t-konormy.
- Výhody: Flexibilita pri modelovaní a interpretácii pravidiel, umožňuje zohľadňovať neurčitosť a nejasnosti vstupných dát.
- Obmedzenia: Komplexnejšie výpočty, ťažšie ladenie a optimalizácia parametrov.

2. **Takagi-Sugeno-Kang fuzzy regulátory**:
- Charakteristika: Tento typ regulátora kombinuje fuzzy pravidlá s lineárnymi výstupnými akciami. Každé pravidlo definuje lineárnu funkciu výstupu, a výstup fuzzy regulátora je váženým priemerom týchto lineárnych funkcií.
- Výhody: Jednoduchšie matematické vyjadrenie, rýchlejšie výpočty, schopnosť pracovať s výstupmi vo forme konkrétnych čísel.
- Obmedzenia: Menej flexibilný pri modelovaní, obmedzený počet výstupných akcií, menšia schopnosť zohľadňovať neurčitosť.

3. **Fuzzy regulátory typu Singleton**:
- Charakteristika: Tento typ regulátora používa jednoduché fuzzy pravidlá s vstupnými a výstupnými premennými reprezentovanými ako singletony (jednobodové fuzzy množiny).
- Výhody: Jednoduchosť implementácie, rýchle výpočty, malé množstvo pravidiel.
- Obmedzenia: Menej flexibilný pri modelovaní komplexnejších systémov, obmedzená schopnosť zohľadňovať neurčitosť.

4. **Adaptívny fuzzy regulátor**: Adaptívne fuzzy regulátory sa prispôsobujúmeniacim sa podmienkam a zmenám v systéme, ktorý riadia. Tieto regulátory môžu meniť svoje pravidlá, váhy pravidiel alebo parametre funkcií príslušnosti na základe spätnej väzby a adaptívnych algoritmov. Týmto spôsobom môžu adaptívne fuzzy regulátory zlepšovať svoju výkonnosť a prispôsobovať sa meniacim sa podmienkam.

5. **Špeciálne navrhnuté fuzzy regulátory**: Okrem týchto základných typov existuje množstvo špeciálne navrhnutých fuzzy regulátorov, ktoré sa prispôsobujú konkrétnym problémom a aplikáciám. Tieto regulátory môžu obsahovať rôzne štruktúry pravidiel, metódy fuzzifikácie a defuzzifikácie, ako aj iné špecifické vlastnosti, ktoré sú vhodné pre daný 

Tieto typy fuzzy regulátorov majú rôzne vlastnosti a výhody v závislosti od konkrétneho problému a požiadaviek. Výber správneho typu regulátora je dôležitý pre úspešné riadenie systému a dosiahnutie požadovaných výsledkov.

____

- ## 10. Popíšte TSK regulátor – vlastnosti, inferenciu a vzťahy voči Mamdaniho typu.
![Lectures - 2023_Страница_057](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/a0b26412-b6a2-4a78-9717-88f389245d57)
![Lectures - 2023_Страница_058](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/2c62a1be-524c-4b33-a8c0-94667879e9f7)

Takagi-Sugeno-Kang (TSK) regulátor je špecifický typ fuzzy regulátora, ktorý sa líši od tradičného Mamdaniho typu. TSK regulátor je založený na pravidlách s "mamkačovským" modelom, kde výstupné pravidlá sú vyjadrené lineárnymi rovnicami. Tento regulátor má niekoľko charakteristík a vzťahov voči Mamdaniho typu:

1. **Výstupné pravidlá**: V TSK regulátore sú výstupné pravidlá vyjadrené ako lineárne rovnice vstupných premenných. Každá výstupná premenná má svoju lineárnu funkciu, ktorá je určená na základe vstupných podmienok. Tieto rovnice umožňujú priamočiare a analytické vyjadrenie výstupu regulátora.

2. **Defuzzifikácia**: V TSK regulátore sa defuzzifikácia vykonáva jednoduchým vypočítaním váženého priemeru výstupov pravidiel. Váhy pravidiel sa určujú na základe pravdepodobnosti pravidiel a funkcie príslušnosti vstupných hodnôt. Výsledná defuzzifikovaná hodnota je lineárnou kombináciou výstupov pravidiel.

3. **Inferencia**: Inferencia v TSK regulátore je založená na metóde tzv. váženej produkcie, ktorá zohľadňuje hodnoty príslušnosti vstupných hodnôt a váhy pravidiel. Vážená produkcia určuje príspevok každého pravidla k výslednému výstupu na základe týchto faktorov.

4. **Transparentnosť**: TSK regulátor je považovaný za transparentnejší v porovnaní s Mamdaniho regulátorom, pretože výsledné pravidlá sú vyjadrené ako lineárne rovnice. Toto umožňuje jednoduchšiu interpretáciu výstupov a vysvetlenie rozhodnutí pri použití regulátora.

Nasledujúce vlastnosti, inferencia a vzťahy voči Mamdaniho typu podrobne popisujú TSK regulátor:

1. **Vlastnosti TSK regulátora**:

- **Lineárne výstupy**: TSK regulátor reprezentuje výstupy pomocou lineárnych funkcií, nie fuzzy množinami. Každá výstupná premenná má priradenú lineárnu funkciu, ktorá je vyjadrená v závislosti od vstupných podmienok a parametrov.

- **Mamkačovský model**: TSK regulátor používa tzv. "mamkačovský" model, kde pravidlá sa vyjadrujú vo forme "ak- potom" rovníc. Každé pravidlo obsahuje antecedent, ktorý popisuje vstupné podmienky, a konsekvent, ktorý určuje výstupnú hodnotu.

- **Vstupné fuzzy množiny**: Vstupné premenné TSK regulátora sú reprezentované pomocou fuzzy množín s funkciou príslušnosti, podobne ako v Mamdaniho type. Avšak, v TSK regulátore sa vstupné fuzzy množiny nepoužívajú priamo pri inferencii, ale slúžia na vyjadrenie antecedentov pravidiel.

2. **Inferencia v TSK regulátore**:

- **Linguistické pravidlá**: TSK regulátor obsahuje fuzzy pravidlá vo forme linguistických výrazov. Každé pravidlo má vlastný antecedent, ktorý obsahuje podmienky na vstupné premenné, a konsekvent, ktorý určuje výstupnú hodnotu.

- **Váhy pravidiel**: Každé pravidlo v TSK regulátore je priradené váha, ktorá určuje dôležitosť tohto pravidla pri vyhodnocovaní výstupu. Váhy pravidiel môžu byť konštantné alebo môžu sa meniť dynamicky v závislosti od podmienok systému.

- **Výstupná lineárna funkcia**: Výstupné premenné v TSK regulátore majú priradenú lineárnu funkciu, ktorá je vyjadrená v závislosti od vstupných podmienok a parametrov pravidla. Táto lineárna funkcia zohľadňuje príslušnosti antecedentov pravidiel a ich váhy.

V porovnaní s Mamdaniho typom regulátora má TSK regulátor výhodu jednoduchšieho matematického modelu a rýchlejšej inferencie. Je vhodný pre aplikácie, kde je potrebná rýchla a analytická odpoveď na základe vstupných podmienok.

____

- ## 11. Popíšte kritériá hodnotenia bázy pravidiel.
![Lectures - 2023_Страница_061](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/b88019ac-c179-409b-9ae8-a46c3edaeb52)
![Lectures - 2023_Страница_062](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/f3cc548b-6846-45c6-939d-95a1681df35b)
![Lectures - 2023_Страница_063](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/b0d55fa9-1cee-4d7a-8c73-350dd76bb29a)
![Lectures - 2023_Страница_064](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/ca3267fb-781e-4db7-aa52-1f7ca20c3e1b)
![Lectures - 2023_Страница_065](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/6aed52b4-3520-4e99-8008-17b5041f7b21)
![Lectures - 2023_Страница_066](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/b02ff6d8-af8a-4d76-82ae-b55d7540d84c)
![Lectures - 2023_Страница_067](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/e971cd7f-1631-427c-869f-40a91699f638)

Pri hodnotení bázy pravidiel v fuzzy regulátore sa zvyčajne zohľadňujú nasledujúce kritériá:

1. **Úplnosť**: Úplnosť bázy pravidiel sa vzťahuje na to, do akej miery pokrýva celý priestor vstupných podmienok. Úplná báza pravidiel zahŕňa pravidlá pre všetky možné kombinácie vstupných podmienok. Vysoká úplnosť zaručuje, že systém dokáže správne reagovať na všetky vstupné situácie.

2. **Konzistentnosť (neprotirečivosť)**: Konzistentnosť bázy pravidiel zabezpečuje, že pravidlá sú navzájom kompatibilné a nevedú k protirečivým výstupom. Pravidlá by nemali byť v rozpore s inými pravidlami a výsledky inferencie by mali byť logicky konzistentné.

3. **Spojitosť**: Spojitosť bázy pravidiel sa týka plynulosti prechodu medzi jednotlivými pravidlami. Spojitá báza pravidiel zabezpečuje, že zmeny vstupných hodnôt vedú k plynulým a očakávaným zmenám výstupných hodnôt. Spojitosť je dôležitá pre správne riadenie systému a eliminuje nežiaduce skoky alebo diskontinuity v hodnotách výstupu.

Tieto kritériá hodnotenia bázy pravidiel majú za cieľ zabezpečiť správne fungovanie fuzzy regulátora a kvalitné riadenie systému. Úplná, konzistentná a spojitá báza pravidiel je dôležitá pre správne inferencie a generovanie presných výstupov. Pri návrhu a hodnotení bázy pravidiel je potrebné venovať pozornosť týmto kritériám a prispôsobiť ich konkrétnym požiadavkám a charakteristikám riadeného systému.

____

- ## 12. Popíšte rozdelenie parametrov ovplyvňujúcich inferenciu fuzzy regulátora a čo vieme vyčítať z regulačnej plochy.
![Lectures - 2023_Страница_069](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/5958fbe0-2d13-49d4-9198-c9356156fdf8)
![Lectures - 2023_Страница_075](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/46b93eb7-7dff-4915-ae17-69101d948b8b)

Inferencia v fuzzy regulátoroch je ovplyvnená rôznymi parametrami, ktoré môžeme rozdeliť do nasledujúcich kategórií:

1. **Parametre pravidiel**: Tieto parametre sa vzťahujú k jednotlivým pravidlám v báze pravidiel. Zahrňujú prahové hodnoty, funkcie príslušnosti pre vstupy a výstupy, váhy pravidiel a metódy inferencie. Tieto parametre určujú, ako sú vstupy kombinované a spracované v rámci fuzzy regulátora a aký výstup je generovaný.

2. **Parametre funkcií príslušnosti**: Funkcie príslušnosti opisujú príslušnosť jednotlivých hodnôt ku fuzzy množinám. Parametre týchto funkcií, ako sú stred, šírka, vrcholová hodnota atď., ovplyvňujú tvar a priebeh funkcie príslušnosti. Zmena týchto parametrov ovplyvňuje interpretáciu hodnôt vstupov a môže mať vplyv na inferenciu.

3. **Parametre defuzzifikácie**: Pri defuzzifikácii sa generované fuzzy výstupy prevedú na konkrétne číselné hodnoty. Parametre defuzzifikačných metód, ako sú váhové funkcie, centroidy, výberové pravidlá a podobne, ovplyvňujú presnosť a správnosť výsledných hodnôt defuzzifikácie.

Regulačná plocha v rámci fuzzy regulátora obsahuje informácie o vzťahu medzi vstupmi a výstupmi. Z tejto plochy je možné vyčítať nasledujúce informácie:

1. **Vzťahy medzi vstupmi a výstupmi**: Regulačná plocha ukazuje, ako sa mení výstup v závislosti od zmien vstupných hodnôt. Z plochy je možné získať informácie o tom, aké vstupné kombinácie vedú k akým výstupným hodnotám. To umožňuje pochopenie vzťahov a trendov v riadenom systéme.

2. **Stabilita systému**: Z regulačnej plochy je možné odvodiť informácie o stabilite systému. Ak je regulačná plocha hladká a kontinuálna, naznačuje to stabilitu a správne riadenie. Naopak, prudké zmeny a nekonzistentné hodnoty na ploche môžu naznačovať nestabilitu systému.

3. **Dynamika systému**: Regulačná plocha môže poskytnúť informácie o dynamike systému. Zmeny v tvaroch a rozsahu plochy môžu naznačovať, ako systém reaguje na rôzne vstupné podmienky a aké sú jeho charakteristické vlastnosti.

Regulačná plocha a parametre fuzzy regulátora sú dôležitými nástrojmi pri analýze a návrhu fuzzy riadiacich systémov. Z týchto informácií môžeme získať cenné poznatky o riadenom systéme a prispôsobiť parametre regulátora pre dosiahnutie želaného riadenia.

____

- ## 13. Popíšte niektoré základné zákonitosti vplyvu funkcií príslušnosti na inferenčný proces fuzzy regulátora.

Funkcie príslušnosti majú významný vplyv na inferenčný proces fuzzy regulátora. Niektoré základné zákonitosti týkajúce sa tohto vplyvu sú:

1. **Úplnosť pokrytia**: Funkcie príslušnosti by mali byť navrhnuté tak, aby správne pokrývali celý priestor vstupných hodnôt. Ak niektoré oblasti priestoru nie sú dostatočne pokryté, môže dôjsť k stratám informácií a chýbajúcim inferenčným možnostiam. Dôležité je zabezpečiť, aby všetky relevantné hodnoty vstupov mali priradené príslušnosti v rámci funkcií príslušnosti.

2. **Prekrývanie funkcií príslušnosti**: Prekrývanie funkcií príslušnosti je dôležité pre hladký prechod medzi hodnotami. Ak existuje priestor prekrývania medzi susednými funkciami príslušnosti, umožňuje to plynulé prechody v inferenčnom procese. Toto prekrývanie zabezpečuje kontinuitu a spojitosť výsledkov inferencie pri meniacich sa hodnotách vstupov.

3. **Vzdialenosť medzi centrami**: Vzdialenosť medzi centrami funkcií príslušnosti ovplyvňuje dôležitosť jednotlivých funkcií pri vyhodnocovaní pravidiel. Väčšia vzdialenosť medzi centrami znamená väčšiu odlišnosť medzi pravidlami a ich váhami, čo môže mať vplyv na výsledky inferencie. Pri návrhu funkcií príslušnosti je dôležité zvážiť vhodnú vzdialenosť medzi centrami na základe špecifík riadeného systému.

4. **Šírka funkcií príslušnosti**: Šírka funkcií príslušnosti ovplyvňuje rozsah, v ktorom je pravidlo aktívne. Väčšia šírka umožňuje pravidlám byť aktívnymi pre širšie rozsahy hodnôt, čo môže viesť k väčšej generalizácii a robustnosti. Naopak, užšie funkcie príslušnosti umožňujú lepšie prispôsobenie sa konkrétnym hodnotám vstupov.

5. **Tvar funkcií príslušnosti**: Tvar funkcií príslušnosti zohľadňuje charakteristické vlastnosti vstupných premenných. Rôzne tvary, ako napríklad trojuholníkové, trapezoidálne alebo gausiánové funkcie príslušnosti, majú rôzne vlastnosti a vhodnosť pre konkrétne aplikácie. Správny výber tvaru funkcií príslušnosti môže viesť k lepším výsledkom inferencie.

6. **Overlapovanie**: Overlapovanie funkcií príslušnosti je kľúčovým aspektom inferenčného procesu. Ak majú funkcie príslušnosti pre rôzne fuzzy množiny vstupov prekrývajúce sa oblasti, umožňuje to efektívnejšie vyhodnocovanie pravidiel, pretože jedno pravidlo môže mať vplyv na viacero fuzzy množín.

7. **Symetria**: Symetrické funkcie príslušnosti, ako napríklad trojuholníkové alebo gaussové funkcie, sú často používané, pretože umožňujú intuitívne vyjadrenie vzťahu medzi vstupmi a výstupmi.

8. **Hranice a špičky**: Hranice funkcií príslušnosti určujú presnosť a rozlíšenie medzi rôznymi vstupnými hodnotami. Ostrejšie hrany môžu poskytnúť väčšiu presnosť a odlíšenie medzi hodnotami, zatiaľ čo mäkšie hrany môžu poskytnúť plynulejšiu a kontinuálnu reakciu na vstupy.

9. **Váhy pravidiel**: Váhy pravidiel určujú dôležitosť jednotlivých pravidiel pri inferencii. Funkcie príslušnosti môžu ovplyvňovať výpočet váh pravidiel a ich správnu interpretáciu. Napríklad, ak funkcie príslušnosti majú vyššiu hodnotu v určitom intervale, môže to viesť k vyššej váhe pravidla pre daný interval.

10. **Kombinácia pravidiel**: V prípade, že sa viacero pravidiel aplikuje na dané vstupy, je potrebné zvoliť vhodnú metódu kombinácie týchto pravidiel. Možnosti zahŕňajú metódy minima, maxima, priemeru, váženého priemeru a iné. Voľba tejto metódy môže ovplyvniť výslednú inferenciu a výstup fuzzy regulátora.

Správny výber a konfigurácia funkcií príslušnosti s ohľadom na tieto zákonitosti je kľúčový pre efektívnu a presnú inferenciu v fuzzy regulátoroch. Je dôležité experimentovať, testovať a prispôsobovať funkcie príslušnosti tak, aby čo najlepšie reprezentovali charakteristiku a vzťahy v riadenom systéme.

____

- ## 14. Popíšte manuálny postup návrhu fuzzy regulátora.

Manuálny postup návrhu fuzzy regulátora je proces, ktorý umožňuje vytvoriť a naladiť fuzzy regulátor na základe expertných znalostí a skúseností s riadeným systémom. Nasleduje podrobný popis tohto postupu:

1. **Štádium analýzy a modelovania**:
- Zozbieranie informácií o riadenom systéme, jeho vstupoch, výstupoch a ich vzťahoch. Tieto informácie môžu pochádzať z fyzikálnych zákonov, experimentov, meraní atď.
- Identifikácia dôležitých premenných a parametrov, ktoré ovplyvňujú chovanie systému.
- Vytvorenie matematického modelu riadeného systému, ktorý popisuje jeho dynamiku a vzťah medzi vstupmi a výstupmi.

2. **Štádium fuzzifikácie**:
- Určenie fuzzy množín pre jednotlivé vstupné a výstupné premenné. Tieto množiny by mali pokrývať celý rozsah hodnôt a zohľadňovať expertné znalosti o riadenom systéme.
- Definícia funkcií príslušnosti pre jednotlivé fuzzy množiny. Funkcie príslušnosti by mali odzrkadľovať expertné znalosti a zohľadňovať charakteristiku a vzťahy v riadenom systéme.
- Priradenie konkrétnych hodnôt vstupov a výstupov k jednotlivým funkciám príslušnosti.

3. **Štádium tvorby bázy pravidiel**:
- Identifikácia relevantných pravidiel na základe expertných znalostí. Tieto pravidlá sú tvorené kombináciou vstupných fuzzy množín a príslušných výstupných akcií.
- Priradenie váh pravidlám, ktoré určujú ich dôležitosť a vplyv na inferenčný proces.

4. **Štádium inferencie**:
- Vyhodnotenie pravidiel na základe aktuálnych vstupných hodnôt. Váhy pravidiel a hodnoty funkcií príslušnosti sú použité na určenie príslušnosti vstupov k jednotlivým pravidlám a výpočet výstupných hodnôt.

5. **Štádium defuzzifikácie**:
- Prevedenie fuzzy výstupov na konkrétne číselné hodnoty.
- Použitie metód defuzzifikácie, ako je napríklad vážený priemer, centroid, metóda najvyššej hodnoty, na výpočet jednej číselnej hodnoty výstupu.

6. **Ladene a optimalizácia**:
- Experimentovanie s rôznymi hodnotami funkcií príslušnosti, váh pravidiel a iných parametrov na dosiahnutie požadovaného správania systému.
- Analýza a porovnávanie výsledkov s referenčnými hodnotami alebo žiadaným správaním systému.
- Prispôsobovanie a optimalizácia parametrov fuzzy regulátora na základe získaných výsledkov a spätnoväzbových informácií.

Tento manuálny postup vyžaduje expertné znalosti a skúsenosti s riadeným systémom. Pravidlá, funkcie príslušnosti a ďalšie parametre regulátora sú definované manuálne na základe znalostí o systéme a jeho požadovanom správaní. Postupne sa experimentuje, testuje a optimalizuje hodnoty parametrov, aby sa dosiahol požadovaný výkon regulátora vzhľadom na riadený systém.

____

- ## 15. Typy adaptačných mechanizmov a priama adaptácia fuzzy systémov – štruktúra a základne delenie.
![Lectures - 2023_Страница_076](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/63d2cfd3-1952-4514-9c25-128dd29d10bd)
![Lectures - 2023_Страница_077](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/27f64712-53e5-4dea-ad96-273c9074afcc)
![Lectures - 2023_Страница_078](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/d2946545-38c1-4a0e-87f0-3ad5acbae09b)
![Lectures - 2023_Страница_079](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/eb44b6df-8885-42b0-ab39-20476d206b23)

Adaptačné mechanizmy v rámci fuzzy systémov umožňujú automatickú úpravu parametrov regulátora na základe spätnoväzbových informácií a optimalizáciu jeho výkonu. Existujú dva hlavné typy adaptačných mechanizmov: self-tuning (samo-nastavovacie) a self-organizing (samo-organizujúce) mechanizmy. Okrem toho, priama adaptácia fuzzy systémov umožňuje priame určovanie parametrov na základe rôznych metód.

1. **Self-tuning (samo-nastavovacie) mechanizmy**:

- Metóda gradientu: Využíva gradientnú optimalizáciu na aktualizáciu parametrov regulátora. Výpočet gradientu sa vykonáva na základe chyby medzi požadovaným a skutočným výstupom, a následne sa upravia váhy a parametre regulátora.
- Metóda najmenších štvorcov: Používa sa na minimalizáciu kvadratickej chyby medzi odozvou systému a požadovaným výstupom. Na základe tejto minimalizácie sa aktualizujú parametre regulátora.
- Genetické algoritmy: Využívajú evolučné metódy a princípy prírodnej selekcie na optimalizáciu parametrov regulátora. Rôzne kombinácie a mutácie parametrov sú testované a hodnotené na základe predom definovaných kritérií.

2. **Self-organizing (samo-organizujúce) mechanizmy**:

- Neurónové siete: Sú založené na modeloch biologických neurónov a ich vzájomnej interakcii. Sú schopné adaptovať váhy a parametre na základe spätnoväzbových informácií. Neurónové siete môžu byť použité na učenie a predikciu vzťahov medzi vstupmi a výstupmi.
- Klastrovanie: Používa sa na identifikáciu vzorov a zoskupenie podobných príkladov. Pomocou klastrovania je možné adaptovať pravidlá fuzzy systému na základe znalostí získaných zo vstupných dát.
- Adaptívne metódy rozdelenia: Využívajú dynamické pridávanie a odstraňovanie pravidiel a fuzzy množín na základe zmeny okolia a potreby presnosti výstupu. Tieto metódy sú schopné adaptovať štruktúru fuzzy systému na základe aktuálnych podmienok.

1. **Štruktúra priamej adaptácie fuzzy systémov**:

- Vstupy: Vstupné signály systému, ktoré sú použité na výpočet výstupov regulátora.
- Fuzzy regulátor: Obsahuje fuzzy množiny, funkcie príslušnosti, bázu pravidiel a adaptačné mechanizmy.
- Výstupy: Výstupné signály regulátora, ktoré sú použité na riadenie riadeného systému.
- Riadený systém: Systém, ktorý má byť riadený a na ktorý pôsobia výstupy fuzzy regulátora.

2. **Základné delenie priamej adaptácie fuzzy systémov**:

a) **Metódy založené na identifikácii**:
- Používajú sa pre odhad parametrov fuzzy regulátora na základe vstupno-výstupných dát z riadeného systému.
- Vykonáva sa identifikácia parametrov na základe optimalizačných techník, ako je napríklad metóda najmenších štvorcov, genetické algoritmy, rojové algoritmy, atď.
- Identifikované parametre sú následne použité pre aktualizáciu parametrov fuzzy regulátora.

b) **Metódy založené na spätnoväzbe**:
- Používajú sa na aktualizáciu parametrov fuzzy regulátora na základe spätnoväzbových informácií z riadeného systému.
- Získané spätnoväzbové informácie sú použité na výpočet chyby regulácie, ktorá slúži ako vstup pre adaptačný mechanizmus.
- Adaptačný mechanizmus aktualizuje parametre fuzzy regulátora na základe chyby regulácie a prispôsobuje ich, aby sa minimalizovala táto chyba.

Priama adaptácia fuzzy systémov umožňuje priame určovanie parametrov regulátora na základe rôznych metód. Niektoré z týchto metód zahŕňajú:

- Inkrementálne modely (Jacobian): Využívajú derivácie a parciálne diferenciácie na výpočet zmien parametrov regulátora vzhľadom k zmene vstupov alebo výstupov systému.
- Gradientové modely: Využívajú gradientné metódy na určenie zmien parametrov regulátora na základe cieľovej funkcie a gradientu tejto funkcie.
- Štatistické modely: Využívajú štatistické metódy a algoritmy na identifikáciu a adaptáciu parametrov regulátora na základe vzorcov a trendov v dátach.
- Interpolačné modely: Využívajú interpoláciu a aproximáciu na určenie hodnôt parametrov regulátora medzi existujúcimi vzorkami alebo pravidlami.
- Symbolické výpočty: Využívajú symbolické metódy a výrazy na určenie parametrov regulátora na základe vzťahov a rovníc popisujúcich riadený systém.
- Genetické algoritmy: Využívajú evolučné metódy a genetické operátory na optimalizáciu parametrov regulátora na základe kritérií fitness a prirodzeného výberu.

Tieto adaptívne metódy a priame adaptácie poskytujú možnosti automatickej úpravy parametrov a štruktúry fuzzy systémov na základe aktuálnych podmienok a potrieb riadeného systému.

Priama adaptácia fuzzy systémov je užitočným nástrojom na automatické naladenie parametrov regulátora na základe skutočných podmienok riadeného systému. Je vhodná pre situácie, kde nie je k dispozícii presný model systému alebo sa systém mení v čase.

____

- ## 16. Procyk-Mamdaniho samoorganizačný fuzzy regulátor – štruktúra, postup vyhodnocovania a základné adaptačné pravidlo. Gradientové prístupy adaptácie.
- ## 17. Spôsoby implementácie základného adaptačného pravidla Procyk-Mamdaniho samoorganizačného fuzzy regulátora a porovnanie ich vlastností. Odpratávač odpadkov.
- ## 18. Fuzzy relácie – definícia, operácie a prepis znalostí z produkčných pravidiel do fuzzy relácie.
- ## 19. Formy reprezentácie znalostí vo fuzzy systémoch a porovnanie kompozičnej inferencie s inferenciou podľa jednotlivých pravidiel.
- ## 20. Fuzzy kognitívne mapy – definícia, spôsob činnosti, manuálny návrh.
- ## 21. Spôsoby implementácie fuzzy kognitívnych máp a manuálny postup návrhu.
- ## 22. Implikátory, ich vzťah k vlastnej inferencii a základné typy implikátorov.
- ## 23. Metódy modus ponens a modus tollens a ich všeobecná forma.
- ## 24. Relácie podobnosti a metóda piatich najbližších susedov.
- ## 25. Hranové operátory – použitie, základné typy hranových operácií.
- ## 26. Systémy pravdivostných hodnôt – Baldwinov systém.
- ## 27. Multidimenzionálne uvažovanie – prehľad. Mizumotov prístup.
- ## 28. Zhluková analýza – definícia a využitie.
- ## 29. Miery neurčitosti fuzzy množín – definícia, vlastnosti a základné typy.
- ## 30. Fuzzy množiny typu 2 – definícia a využitie v regulácii.
- ## 31. Metódy k-means, fuzzy c-means a ich porovnanie.
