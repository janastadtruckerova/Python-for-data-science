# Python-for-data-science
# Python for Data Science 📊 – Kolekcia Dátových Projektov

---

Vitajte v repozitári **Python for Data Science**! 👋

Tento repoozitár slúži ako **praktická kolekcia dátových projektov a prípadových štúdií** s využitím programovacieho jazyka Python. Mojím cieľom je demonštrovať aplikáciu kľúčových dátových vedeckých techník a knižníc na reálnych (alebo simulovaných) dátach, od zberu a čistenia až po analýzu a vizualizáciu.

---

## Čo tu nájdete? 📚

Každý projekt v tomto repozitári je samostatná štúdia, ktorá zvyčajne obsahuje:

* **Google colab Notebook(y):** Podrobný kód s komentármi, vysvetleniami a výsledkami -
* **Dátové súbory:** linky na datesety alebo csv súbory použité v projektoch
* **Stručný popis:** Stručný popis projektu.
* **Vizualizácie:** Grafy a iné vizuálne výstupy analýzy sú súčasťou notebookov.

---

## Prehľad projektov (Príklady) ✨

Tu je zoznam aktuálnych  dátových projektov v tomto repozitári:
Tento zoznam budem priebežne aktualizovať s novými projektmi a ich detailmi
## 📊 Analýza vplyvu AI a automatizácie na pracovné pozície

Tento projekt sa zameriava na analýzu vplyvu AI a automatizácie na pracovné pozície, odvetvia a zručnosti. Identifikuje pozície, ktoré sú najviac ohrozené automatizáciou.  Použitý dataset:https://www.kaggle.com/datasets/uom190346a/ai-powered-job-market-insights
Google colab notebook projektu. AI job market.ippymb.

Podrobnejšia analýza je uvedená v článku na Linkedin:

https://www.linkedin.com/pulse/vplyv-umelej-inteligencie-ui-automatiz%C3%A1cie-na-poz%C3%ADcie-stadtruckerova-k0ife/?trackingId=84DAQvhcopQeoUP3IPnIPA%3D%3D

## 📈 Analýza HDP a Strednej Dĺžky Života

**Cieľ:** Tento projekt sa zameriava na hĺbkovú exploráciu dynamiky vzťahu medzi hrubým domácim produktom (HDP) a strednou dĺžkou života pri narodení (LEABY) v šiestich geograficky a ekonomicky rozmanitých krajinách: Čile, Mexiko, Nemecko, USA, Čína a Zimbabwe. Analýza pokrýva obdobie od roku 2000 do roku 2015.

**Kľúčové aspekty projektu:**
* **Historické trendy:** Skúmanie vývoja HDP a LEABY v čase pre každú krajinu.
* **Vzájomná korelácia:** Vizualizácia a interpretácia vzťahu medzi HDP a LEABY.
* **Prípadové štúdie:** Detailný pohľad na unikátne trajektórie rozvoja (napr. rast Číny, zotavenie Zimbabwe).
* **Použité techniky:** Python (Pandas, NumPy, Matplotlib, Seaborn), štatistické vizualizácie vrátane logaritmických škál a `FacetGrid`.

**[Celý projekt nájdete tu](gdp_leaby_analysis/README.md)**

### ** Logistická Regresia - Klasifikácia rakoviny prsníka**
* **Cieľ:** Vytvoriť model, ktorý s vysokou presnosťou predpovedá, či je nádor zhubný alebo nezhubný.
* **Použité metódy:** Prieskumná analýza dát (EDA), Logistická Regresia, vyhodnotenie metrikami (Confusion Matrix, Recall), overenie stability pomocou krížovej validácie.
* **Súbor:** [Logistická regresia.ipynb](https://github.com/Tvoje_Meno/Python-for-datascience/blob/main/Logistická%20regresia.ipynb)

### ** Predikcia COVID 19 pomocov modelov ARIMA a LTMS**
* **Cieľ:** Tento projekt predstavuje porovnávaciu analýzu a predikciu denných prípadov COVID-19 na Slovensku s využitím dvoch odlišných prístupov: klasického štatistického modelu **ARIMA** a pokročilej neurónovej siete **LSTM**.
Cieľom projektu bolo nielen predpovedať budúci vývoj, ale aj demonštrovať schopnosti oboch modelov pri práci s časovými radmi a vyhodnotiť ich presnosť na základe reálnych dát.
* **Použité metódy:** 
* **Súbor:** https://github.com/janastadtruckerova/Python-for-data-science/tree/main/predikcia%20COVID%2019(ďalšie projekty) ...

## Použité nástroje a knižnice 🛠️
* **Jazyk:** Python 3.x
* **Dátová analýza a spracovanie:** `pandas`, `numpy`, `scikit-learn`
* **Štatistické modelovanie:** `statsmodels`
* **Hlboké učenie (Deep Learning):** `tensorflow`, `keras`
* **Vizualizácia:** `matplotlib`, `seaborn`


V týchto projektoch sa primárne využívajú nasledujúce nástroje a knižnice:

* **Python 3.x**
* **Google colab**
* **Pandas:** Manipulácia a analýza dát.
* **NumPy:** Numerické výpočty.
* **MSeaborn:** Vizualizácia dát.
* **Scikit-learn:** Strojové učenie.
* **... a ďalšie špecifické pre jednotlivé projekty!**

---

## Ako začať? 🚀

1.  **Klonujte si repozitár:**
    ```bash
    git clone [https://github.com/vase_meno_uzivatela/Python-for-Data-Science.git](https://github.com/vase_meno_uzivatela/Python-for-Data-Science.git)
    ```
2.  **Prejdite do priečinka projektu:**
    ```bash
    cd Python-for-Science
    ```
3.  **Vytvorte si virtuálne prostredie (odporúčané):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # Pre Linux/macOS
    # alebo
    .\venv\Scripts\activate  # Pre Windows
    ```
4.  **Nainštalujte potrebné knižnice:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Uistite sa, že máte súbor `requirements.txt` s uvedenými všetkými závislosťami pre vaše projekty.)*
5.  **Spustite Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Vo vašom prehliadači sa otvorí Jupyter rozhranie, kde môžete prehliadať a spúšťať `.ipynb` súbory jednotlivých projektov.

---

## Prispievanie 🤝

Aj keď je tento repozitár primárne mojou osobnou zbierkou projektov, akékoľvek návrhy na vylepšenia, opravy alebo nové nápady na projekty sú vítané!

1.  Forknite si tento repozitár.
2.  Vytvorte novú vetvu (`git checkout -b feature/nazov-projektu`).
3.  Urobte svoje zmeny.
4.  Otvorte Pull Request.

---

## Licencia 📄

Tento projekt je licencovaný pod licenciou MIT. Viac informácií nájdete v súbore [LICENSE](LICENSE).

---

## Kontakt ✉️

Ak máte akékoľvek otázky, návrhy alebo sa chcete spojiť:

* **GitHub Issues:** Použite sekciu Issues tohto repozitára.
* **LinkedIn:** https://www.linkedin.com/in/jana-stadtruckerov%C3%A1-7801779b/
  

---

**Ďakujem za návštevu a dúfam, že vás moje dátové projekty inšpirujú!** 🚀
