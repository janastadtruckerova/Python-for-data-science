# Analýza Vplyvu automatizácie a umelej intelignecie (AI( na pracovné pozície

## Úvod

Tento projekt  umožní preskúmať vplyv AI a automatizácie na rôzne pracovné pozície, odvetvia a zručnosti. Budeme  identifikovať, ktoré pozície sú najviac ohrozené, ktoré vznikajú a aké zručnosti sú žiadané v AI ére.

Cieľ projektu: Preskúmať dataset, identifikovať a vizualizovať vzťahy medzi úrovňou prijatia AI, rizikom automatizácie, potrebnými zručnosťami a rastovými projekciami pre rôzne typy pracovných pozícií a odvetví.

## Dáta

Použitý dataset
AI-Powered Job Market Insights
a synthetic but realistic snapshot of the modern job market on the role of AI
link na dataset: https://www.kaggle.com/datasets/uom190346a/ai-powered-job-market-insights

## Metodika

Analýza zahŕňala nasledujúce kroky:

1.  **Načítanie a úvodné preskúmanie dát** Načítanie datasetu a získanie základných informácií a jeho štruktúre a obsahu
2.  **Čistenie a príprava dát:** Zmena dátových typov premenných
3.  **Exploračná anaalýza (EDA)** Rozdelenie úrovne adaptácie AI, Riziko automatizácie - Ktorá kategória rizika dominuje?, Riziko automatizácia podľa jednotlivých pracovných pozícií - Ktoré pozície sú najviac ohrozené automatizáciou?, Riziko automatizácie podľa odvetví - Kotré odvetvia sú najviac ohrozené automatizáciou?, Rast pozícií - Firmy s vyššou mierou adaptácie AI - vyšší rast pracovných pozícií, Najčastejšie požadované zručnosti, Vzťah medzi AI_Adoption_Level a Job_Growth_Projection, Vzťah medzi Required_Skills a Salary_USD, Vzťah medzi Automation_Risk (riziko automatizácie) a Job_Growth_Projection (projekcia rastu pozícií),
4.   **Vizualizácie** Vytvorenie vizualizácií pomocou knižníc Matplotlib a Seaborn



## Vizualizácie
Všetky vizualizácie najdete v priečinku oputputs(visualisations

## Ako spustiť projekt

Na spustenie tejto analýzy lokálne potrebujete nainštalovať Python (odporúča sa verzia 3.x) a nasledujúce knižnice:

* `pandas`
* `matplotlib`
* `seaborn`

Knižnice môžete nainštalovať pomocou pip:
`pip install pandas matplotlib seaborn`

1.  Uistite sa, že máte vo svojom repozitári vytvorenú štruktúru priečinkov:
    `ai_job_market_analysis/data/`
    `ai_job_market_analysis/notebooks/`
    `ai_job_market_analysis/outputs/visualizations/`
2.  Umiestnite dátový súbor do priečinka `data/`.
3.  Umiestnite Jupyter Notebook (`.ipynb` súbor s analýzou) do priečinka `notebooks/`.
4.  Otvorte Jupyter Notebook (napr. cez `jupyter notebook` v termináli) a spustite bunky.
5.  Vygenerované vizualizácie sa uložia do priečinka `outputs/visualizations/`.

## Technológie

* Python 3.x
* Jupyter Notebook
* Pandas (pre manipuláciu s dátami)
* Matplotlib (pre vizualizácie)
* Seaborn (pre pokročilé štatistické vizualizácie)
  

---
