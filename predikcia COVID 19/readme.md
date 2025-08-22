# Predikcia šírenia COVID-19: Porovnanie modelov ARIMA a LSTM

Tento projekt predstavuje porovnávaciu analýzu a predikciu denných prípadov COVID-19 na Slovensku s využitím dvoch odlišných prístupov: klasického štatistického modelu **ARIMA** a pokročilej neurónovej siete **LSTM**.

Cieľom projektu bolo nielen predpovedať budúci vývoj, ale aj demonštrovať schopnosti oboch modelov pri práci s časovými radmi a vyhodnotiť ich presnosť na základe reálnych dát.

## Použité technológie a knižnice

* **Jazyk:** Python 3.x
* **Dátová analýza a spracovanie:** `pandas`, `numpy`, `scikit-learn`
* **Štatistické modelovanie:** `statsmodels`
* **Hlboké učenie (Deep Learning):** `tensorflow`, `keras`
* **Vizualizácia:** `matplotlib`, `seaborn`

## Štruktúra projektu

Projekt je rozdelený do dvoch samostatných notebookov, ktoré sa venujú jednotlivým modelom:

1.  `Predikcia COVID 19.ipynb`: Tento notebook sa zameriava na predikciu pomocou modelu ARIMA. Obsahuje:
    * Načítanie a čistenie dát.
    * Analýzu stacionarity (Augmented Dickey-Fuller test).
    * Identifikáciu parametrov (ACF a PACF grafy).
    * Trénovanie, predikciu a vyhodnotenie modelu.

2.  `LSTM covid 19.ipynb`: Tento notebook využíva pokročilú neurónovú sieť LSTM. Obsahuje:
    * Prípravu dát pre neurónové siete (škálovanie a vytváranie sekvencií).
    * Architektúru a trénovanie modelu LSTM.
    * Predikciu a vyhodnotenie výkonu modelu.

## Záverečné zhrnutie a porovnanie

Výsledky oboch modelov boli porovnané pomocou metrík ako Mean Absolute Error (MAE) a Root Mean Squared Error (RMSE).

V tomto projekte sa model **LSTM** ukázal ako presnejší vďaka svojej schopnosti modelovať komplexné a nelineárne vzory v dátach. Model **ARIMA** však zostáva silným nástrojom pre rýchle a spoľahlivé predikcie lineárnych časových radov.

**Kľúčové zistenia z projektu:**
* Metrika	Model SARIMA	Model LSTM
Mean Absolute Error (MAE)	180.89	67.78
Root Mean Squared Error (RMSE)	291.31	109.12


MAE (Mean Absolute Error) predstavuje priemernú absolútnu odchýlku medzi predpovedanými a skutočnými hodnotami. Čím nižšia je táto hodnota, tým je model presnejší.

RMSE (Root Mean Squared Error) je podobná metrika, ale silnejšie penalizuje väčšie chyby v predikcii. Podobne ako pri MAE, aj tu platí, že nižšia hodnota znamená lepšiu presnosť.

Záverečné hodnotenie

Výsledky ukazujú, že model LSTM bol oveľa presnejší pri predpovedi nových prípadov. Je to preto, že LSTM siete, ako typ neurónových sietí, sú navrhnuté tak, aby dokázali zachytiť komplexné a nelineárne vzory v dátach, ktoré tradičné štatistické modely ako SARIMA nemusia byť schopné identifikovať. Vzhľadom na povahu dát (vývoj pandémie) sa zložitejšie modely, ktoré dokážu nájsť hlbšie závislosti, osvedčili ako účinnejšie.
* 

---

> Jana Stadtruckerová
>
> Dátum dokončenia: 22.8.2025
>
> https://www.linkedin.com/in/jana-stadtruckerov%C3%A1-7801779b/
> 
