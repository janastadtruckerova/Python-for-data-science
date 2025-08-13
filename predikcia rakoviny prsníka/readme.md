# Diagnostika rakoviny prsníka s Logistickou Regresiou

#### Prehľad projektu
Tento projekt predstavuje implementáciu a vyhodnotenie klasifikačného modelu na diagnostiku rakoviny prsníka. Využíva dataset **Breast Cancer Wisconsin Diagnostic**, ktorý obsahuje merania bunkových jadier zo vzoriek pacientov. Hlavným cieľom bolo vytvoriť model, ktorý dokáže spoľahlivo klasifikovať vzorky ako **benígne (nezhubné)** alebo **malígne (zhubné)** s dôrazom na interpretovateľnosť a minimalizáciu kritických chýb.

#### Kľúčová metodológia
1.  **Prieskumná analýza dát (EDA):** Analýza distribúcie cieľovej premennej a vizualizácia kľúčových príznakov.
2.  **Modelovanie:** Použitie **Logistickej Regresie** ako hlavného modelu, pretože ponúka vysokú presnosť a vynikajúcu interpretovateľnosť.
3.  **Vyhodnotenie:** Meranie výkonu modelu pomocou metrík ako `Accuracy`, `Confusion Matrix` a `Classification Report`.
4.  **Overenie stability:** Použitie **krížovej validácie** na overenie, že výkon modelu je stabilný a robustný.
5.  **Interpretácia:** Analýza **koeficientov** modelu na identifikáciu najdôležitejších príznakov, ktoré ovplyvňujú diagnózu.

#### Najdôležitejšie výsledky a závery
* **Vysoká presnosť:** Model dosiahol stabilnú presnosť **98.8%** na testovacej množine.
* **Minimalizácia kritických chýb:** Vďaka krížovej validácii a optimalizácii modelu nebola zaznamenaná **žiadna chyba typu *False Negative*** (zhubný nádor označený ako nezhubný), čo je v medicínskej diagnostike kľúčové.
* **Interpretovateľnosť:** Analýza koeficientov potvrdila, že najväčší vplyv na predikciu majú príznaky ako `worst concave points` a `worst perimeter`, čo má medicínsku relevanciu.

#### Vizualizácie
**Matica zámeny (Confusion Matrix)**
<img width="513" height="471" alt="image" src="https://github.com/user-attachments/assets/0b22a99f-8c66-43c2-9ab6-1b1d93846497" />







**Vplyv príznakov (Koeficienty)**
<img width="1144" height="702" alt="image" src="https://github.com/user-attachments/assets/d7efc6b2-0cb7-4336-92cc-d02d69d15ea2" />


#### Technológie
* Python 3.x
* Pandas
* Scikit-learn
* Numpy
* Matplotlib
* Seaborn

#### Ako spustiť projekt
1.  Klonujte repozitár: `git clone [odkaz na váš repozitár]`
2.  Nainštalujte potrebné knižnice: `pip install -r requirements.txt`
3.  Spustite Jupyter Notebook.

#### Živá demo aplikácia (Gradio)
Pre interaktívnu ukážku modelu, kde môžete zadávať vlastné hodnoty a získať predikciu v reálnom čase, navštívte demo aplikáciu:
https://0647daf170d44c4aab.gradio.live/
*Upozornenie: Tento odkaz je dočasný a funkčný len vtedy, keď je notebook spustený.*
---
**Autor:** Jana Stadtruckerová
**Kontakt:** https://www.linkedin.com/in/jana-stadtruckerov%C3%A1-7801779b/
