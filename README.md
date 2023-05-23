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
- ## 11. Popíšte kritériá hodnotenia bázy pravidiel.
- ## 12. Popíšte rozdelenie parametrov ovplyvňujúcich inferenciu fuzzy regulátora a čo vieme vyčítať z regulačnej plochy.
- ## 13. Popíšte niektoré základné zákonitosti vplyvu funkcií príslušnosti na inferenčný proces fuzzy regulátora.
- ## 14. Popíšte manuálny postup návrhu fuzzy regulátora.
- ## 15. Typy adaptačných mechanizmov a priama adaptácia fuzzy systémov – štruktúra a základne delenie.
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
![Lectures - 2023_Страница_194](https://github.com/girgibon/fuzzy-logic/assets/93397589/c5469fe0-26c9-4308-99b9-1797367ff4e1)
![Lectures - 2023_Страница_190](https://github.com/girgibon/fuzzy-logic/assets/93397589/84efc31d-3504-464f-bcb5-1dc8b0b13c84)
![Lectures - 2023_Страница_191](https://github.com/girgibon/fuzzy-logic/assets/93397589/86da1091-3e99-47a6-a6d4-e80ba3f9a18e)
![Lectures - 2023_Страница_192](https://github.com/girgibon/fuzzy-logic/assets/93397589/b4dad203-2c87-42fa-a598-bcf9f353929d)
![Lectures - 2023_Страница_193](https://github.com/girgibon/fuzzy-logic/assets/93397589/565a2a81-f4f6-4215-9b5a-37e59c1f88db)



