# Analýza a Predikcia Platov na Globálnom Trhu Práce v AI

## Úvod

Tento projekt je komplexná analýza a predikcia platov v sektore umelej inteligencie (AI), so zameraním na mzdové trendy v rokoch 2024 a 2025. Hlavným cieľom bolo nielen poskytnúť cenné poznatky o tomto dynamickom odvetví, ale aj vytvoriť prediktívny model, ktorý dokáže s vysokou presnosťou odhadnúť plat AI profesionála na základe kľúčových faktorov.

Výstupom projektu je detailná analytická správa (v dvoch prepojených notebookoch) a interaktívna webová aplikácia na predikciu platov.

---

### **🚀 Ciele a Kľúčové Otázky Analýzy**

Hlavným cieľom tejto analýzy bolo odpovedať na nasledujúce otázky a následne vybudovať model:

* Aké sú aktuálne mzdové trendy pre AI špecialistov naprieč rôznymi úrovňami skúseností, krajinami a typmi spoločností?
* Ako sa líšia platy pre zamestnancov pracujúcich na diaľku (remote) v porovnaní s tými, ktorí pracujú z kancelárie?
* Ktoré zručnosti, pozície a lokality majú najväčší vplyv na potenciál zárobku v oblasti AI?
* **Aký presný model vieme vybudovať na predikciu platu na základe kľúčových faktorov?**

---

### **📊 Kľúčové Zistenia a Výsledky**

* **Skúsenosti sú dôležité:** Mzdy pre AI profesionálov exponenciálne rastú s úrovňou skúseností.
* **Geografia hrá kľúčovú rolu:** USA, Švajčiarsko, Nórsko a Dánsko dominujú rebríčku priemerných AI miezd.
* **Veľkosť spoločnosti a plat:** Väčšie spoločnosti vo všeobecnosti ponúkajú vyššie mzdy.
* **Prekvapivá flexibilita:** Remote práca v AI nemusí nutne znamenať nižší plat.
* **Výkon prediktívneho modelu:** Po implementácii modelov lineárnej regresie a Random Forest sa dosiahol robustný výsledok. Náš finálny model Random Forest dosiahol nasledujúce kľúčové metriky:
    * **Mean Absolute Error (MAE):** približne **[Tvoja hodnota]** USD. Model v priemere odhaduje plat s chybou **[Tvoja hodnota]** USD.
    * **R-squared ($R^2$):** približne **[Tvoja hodnota]**. Model dokáže vysvetliť **[Tvoja hodnota]%** variability v platoch.

---

### **🛠️ Použité Nástroje a Metodológia**

Projekt bol rozdelený do dvoch hlavných fáz, z ktorých každá je podrobne opísaná v samostatnom Jupyter Notebooku.

1.  **Analýza a prieskumná analýza dát (EDA):**
    * Tento proces je detailne zachytený v notebooku **[notebook_analýza.ipynb]**.
    * **Zber a načítanie dát:** Využitie verejne dostupného datasetu z Kaggle.
    * **Čistenie a predbežná úprava dát:** Riešenie chýbajúcich hodnôt a premapovanie kategorických premenných.
    * **Vizualizácia dát:** Tvorba grafov pre jasnú prezentáciu zistení.

2.  **Modelovanie a nasadenie:**
    * Tento proces je opísaný v notebooku **[notebook_modelovanie.ipynb]**, ktorý nadväzuje na zistenia z EDA.
    * **Predspracovanie dát:** Príprava dát pre model, vrátane **One-Hot Encodingu** kategorických premenných.
    * **Trénovanie modelov:** Porovnanie jednoduchého modelu **Lineárnej Regresie** s výkonným **Random Forest Regressorom**.
    * **Hodnotenie modelov:** Vyhodnotenie výkonu modelov pomocou metrík MAE, MSE a $R^2$.
    * **Nasadenie modelu:** Nasadenie finálneho modelu do jednoduchej interaktívnej aplikácie pomocou knižnice Gradio.

---

### **🚀 Aplikácia na predikciu platu**

Súčasťou projektu je interaktívna aplikácia postavená na Gradio, ktorá umožňuje na základe vybraných parametrov predpovedať plat. Môžete si ju spustiť lokálne pomocou `app.py`.

[Vlož sem screenshot tvojej Gradio aplikácie]

---

### **📊 Dataset**

Pre túto analýzu bol použitý dataset "AI Job Market & Salary Trends 2024-2025" z platformy Kaggle.
* **Zdroj:** https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025
   

### **🔗 Obsah Repozitára**

* `notebook_analýza.ipynb`: Detailná prieskumná analýza dát.
* `notebook_modelovanie.ipynb`: Kompletný proces predspracovania, modelovania, hodnotenia a nasadenia.
* `app.py`: Python skript pre Gradio aplikáciu.
* `trained_model.pkl`: Uložený finálny model.
* `ai_salaries_2025.csv`: Vstupný dataset.
* `README.md`: Tento súbor.

---

### **💻 Použité Knižnice (závislosti)**

-   Python
-   `pandas`
-   `numpy`
-   `matplotlib` / `seaborn`
-   `scikit-learn`
-   `gradio`
-   `joblib` (na uloženie modelu)

---

### **Kontakt**

Ak máte otázky, pripomienky alebo sa chcete spojiť, neváhajte ma kontaktovať cez LinkedIn.

[**Môj LinkedIn profil**]https://www.linkedin.com/in/jana-stadtruckerov%C3%A1-7801779b/
---
