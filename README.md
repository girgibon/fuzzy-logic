# Answers for Fuzzy Systems Exam - 2023

- ## 1. Definícia fuzzy množiny a charakteristiky popisujúce funkciu príslušnosti.

**Fuzzy množina je matematický koncept, ktorý rozširuje tradičnú teóriu množín o možnosť priradiť prvkom množiny stupne príslušnosti. Tieto stupne príslušnosti sú reprezentované hodnotami v intervale medzi 0 a 1, pričom hodnota 0 znamená úplnú nepripradivosť prvku do množiny a hodnota 1 znamená úplnú príslušnosť prvku do množiny.**

Charakteristiky popisujúce funkciu príslušnosti určujú, ako je priradený stupeň príslušnosti jednotlivým prvkom množiny. Existuje niekoľko typických charakteristík funkcií príslušnosti, ktoré sa používajú pri modelovaní fuzzy množín. Niektoré z týchto charakteristík zahŕňajú:

![image](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/b2f8aba0-37d4-449d-b110-29ab3fee0765)
![image](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/bea870ad-40b1-4ee2-804a-c7de780e6a6f)

#### CHATGPT:
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

#### CHATGPT
1. **Univerzum**: Univerzum je súbor všetkých možných hodnôt, ktoré lingvistická premenná môže nadobudnúť. Napríklad, ak hovoríme o premenných ako "teplota" alebo "rýchlosť", univerzum by mohlo byť definované ako interval reálnych čísel.

2. **Príslušnosť**: Každá hodnota v univerze je priradená k niektorej lingvistickej množine. Príslušnosť určuje, do akej miery daná hodnota patrí do danej množiny. Príslušnosť môže byť vyjadrená ako číselný stupeň v intervale medzi 0 a 1.

3. **Lingvistické termíny**: Lingvistická premenná obsahuje lingvistické termíny, ktoré predstavujú rôzne kategórie alebo hodnoty v rámci danej premennej. Tieto termíny sú definované pomocou funkcií príslušnosti, ktoré určujú, ako sa hodnoty priradzujú k jednotlivým termínom.

**Lingvistické premenné majú veľký význam v oblasti umelého inteligentného spracovania a rozhodovania, pretože umožňujú modelovať a pracovať s ľudskými konceptmi a jazykom.** Tieto premenné nám umožňujú zahrnúť nejasnosti a vaguity do procesu rozhodovania a logického vyhodnocovania, čo je veľmi užitočné pri riešení problémov v prostredí s neistotou a nejasnosťou.

____

- ## 3. Operácie s fuzzy množinami – základné delenie a ich definície.

**Operácie s fuzzy množinami sa používajú na manipuláciu a kombinovanie hodnôt fuzzy množín.**
![Lectures - 2023_Страница_018](https://github.com/CoolmixZero/fuzzy-logic/assets/107999456/45bc99b4-fba8-4f8b-b9c4-3c18210be23c)

#### CHATGPT
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

#### CHATGPT

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
- ## 7. Popíšte úlohu fuzzifikácie a defuzzifikácie a uveďte základné metódy.
- ## 8. Kritériá hodnotenia defuzzifikačných metód.
- ## 9. Základné delenie fuzzy regulátorov a ich stručná charakteristika.
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
