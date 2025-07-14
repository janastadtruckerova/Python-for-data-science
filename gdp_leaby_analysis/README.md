# Analýza Vzťahu Medzi HDP a Strednou Dĺžkou Života (2000-2015)

## Úvod

Tento projekt skúma dynamiku vzťahu medzi hrubým domácim produktom (HDP) a strednou dĺžkou života pri narodení (Life Expectancy at Birth - LEABY) v šiestich geograficky a ekonomicky rozmanitých krajinách. Analýza pokrýva obdobie od roku 2000 do roku 2015, čo nám umožňuje pozorovať dlhodobé trendy, vplyv globálnych udalostí (ako napríklad finančná kríza v roku 2008/2009) a individuálne trajektórie rozvoja.

**Analyzované krajiny:** Čile, Mexiko, Nemecko, Spojené štáty americké, Čína, Zimbabwe.

## Dáta

Dáta použité v tejto analýze boli získané zo **Svetovej banky (World Bank Data)** a zahŕňajú ročné hodnoty pre HDP (aktuálne USD) a Strednú dĺžku života pri narodení pre každú zo šiestich vybraných krajín. Hoci sú k dispozícii aj novšie dáta, zvolené časové okno (2000-2015) bolo strategicky vybrané pre hĺbkové preskúmanie kľúčových transformačných procesov a dynamiky vzťahu medzi premennými v danom období.

## Metodika

Analýza postupovala nasledovne:

1.  **Načítanie a predbežná explorácia dát:** Načítanie dát do DataFrame, overenie štruktúry a základná deskriptívna štatistika (priemer, medián, štandardná odchýlka) pre identifikáciu celkových rozsahov a distribúcií premenných. Pozornosť bola venovaná najmä šikmosti dát HDP a LEABY.
2.  **Agregované trendy:** Výpočet a vizualizácia ročných priemerov a mediánov HDP a strednej dĺžky života pre celú skupinu krajín, s cieľom identifikovať globálne makro-trendy. Pre HDP bola použitá logaritmická škála pre lepšiu interpretovateľnosť.
3.  **Individuálne trendy krajín:** Vizualizácia vývoja HDP a strednej dĺžky života pre každú krajinu samostatne, s použitím dvoch osí Y (sekundárna os pre LEABY), aby bolo možné sledovať koevolúciu týchto dvoch ukazovateľov v každej krajine.
4.  **Analýza vzťahu HDP a LEABY:** Preskúmanie korelácie medzi HDP a strednou dĺžkou života pomocou bodových grafov (`scatter plots`). Prehľadnosť bola zabezpečená použitím logaritmickej škály pre HDP a vizualizáciou kľúčových rokov (2000 a 2015) alebo dynamického zobrazenia vývoja v čase.
5.  **Zhrnutie a závery:** Identifikácia kľúčových zistení, diskusií o implikáciách a návrh ďalších otázok pre budúci výskum.

## Kľúčové Zistenia

* **Všeobecný pokrok:** Počas rokov 2000-2015 bol zaznamenaný konzistentný rast ako v HDP, tak aj v strednej dĺžke života naprieč väčšinou vybraných krajín.
* **Silná pozitívna korelácia:** Grafy jasne demonštrujú pozitívny vzťah medzi HDP a LEABY – s rastúcim bohatstvom krajiny sa vo všeobecnosti zlepšuje aj dĺžka života.
* **Fenomenálny rast Číny:** Čína preukázala mimoriadny ekonomický rast, sprevádzaný výrazným zlepšením strednej dĺžky života, čím sa posunula výrazne vpred v oboch metrikách.
* **Príbeh zotavenia Zimbabwe:** Napriek počiatočným výzvam a poklesu, Zimbabwe zaznamenalo pozoruhodné zlepšenie strednej dĺžky života, hoci ekonomicky zaostávalo za ostatnými.
* **Stabilita rozvinutých ekonomík:** Nemecko a USA si udržali vysoké úrovne oboch ukazovateľov s konzistentným, no umiernenejším rastom.
* **Odlišné trajektórie:** Napriek všeobecnému trendu, jednotlivé krajiny vykazujú jedinečné cesty rozvoja, ovplyvnené špecifickými ekonomickými, sociálnymi a politickými faktormi.

## Vizualizácie

V priebehu analýzy boli vytvorené rôzne vizualizácie na ilustráciu kľúčových zistení. Niektoré z nich sú priložené v priečinku `outputs/visualizations/`:

* Globálny trend strednej dĺžky života (Priemer a Medián)
* Globálny trend HDP (Priemer a Medián, logaritmická škála)
* Bodové grafy vzťahu HDP a strednej dĺžky života pre rok 2000 a 2015
* Mriežky grafov zobrazujúce vývoj LEABY a HDP pre každú krajinu samostatne.
    *(Môžeš pridať konkrétne obrázky do README, GitHub to podporuje.)*

## Ako spustiť projekt

Na spustenie tejto analýzy lokálne potrebujete nainštalovať Python (odporúča sa verzia 3.x) a nasledujúce knižnice:

* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `plotly` (ak použijete animované grafy)
* `kaleido` (ak chcete exportovať Plotly grafy ako statické obrázky/videá)

Knižnice môžete nainštalovať pomocou pip:
`pip install pandas numpy matplotlib seaborn plotly kaleido`

1.  Naklonujte tento repozitár: `git clone https://dizionari.corriere.it/dizionario_latino/Latino/R/repono.shtml`
2.  Navigujte do priečinka `notebooks/`.
3.  Otvorte `data_analysis.ipynb` v Jupyter Lab alebo Jupyter Notebook.
4.  Spustite bunky v notebooku pre opätovné vytvorenie analýzy a vizualizácií.

## Technológie

* Python 3.x
* Jupyter Notebook
* Pandas (pre manipuláciu s dátami)
* NumPy (pre numerické operácie, logaritmické transformácie)
* Matplotlib (pre základné vizualizácie)
* Seaborn (pre pokročilé štatistické vizualizácie)
* Plotly (pre interaktívne a animované grafy - voliteľné)

---
