Annual Cause-of‐Death Numbers & GDP Analysis


This project investigates the relationship between annual cause-of-death numbers and GDP (Gross Domestic Product) across countries over time. The main work is captured in the notebook annual-death-gdp.ipynb.
Key goals:

Clean and explore a dataset of cause-of-death counts (by country / year) and GDP data.

Perform exploratory data analysis (EDA) to identify patterns/trends.

Build simple machine-learning models to examine how GDP (and potentially other variables) relate to death counts (or death rates) for different causes.

Provide insights and visualisations to better understand global health and economic links.

Contents

annual-death-gdp.ipynb — Jupyter Notebook containing the full workflow: data loading, cleaning, EDA, modelling, results.

Data files (if included) — e.g., CSVs for cause-of-death counts, GDP, country metadata.

(Optional) any supporting scripts/modules for preprocessing.

This README.md file with project description, setup instructions, usage, etc.

Requirements / Setup

Make sure you have the following installed:

Python 3.x

Jupyter Notebook / JupyterLab

Key Python libraries:

pip install pandas numpy matplotlib seaborn scikit-learn


(Optional) If using other libraries (e.g., XGBoost, statsmodels) add them likewise.

 How to run

Clone this repository:

git clone https://github.com/Hiba-Khaleel/Annual-cause-death-numbers-ML.git
cd Annual-cause-death-numbers-ML


Make sure the data files referenced in annual-death-gdp.ipynb are present (or adjust paths).

Open and run the notebook:

jupyter notebook annual-death-gdp.ipynb


or open via JupyterLab.

Follow the sections in the notebook:

Data loading & overview

Data cleaning & preprocessing

Exploratory visualisations

Feature engineering (e.g., death rate per population, GDP per capita)

Modelling (train/test split, ML algorithms, evaluation)

Discussion of results and conclusions.

What to expect

Cleaned dataset combining cause-of-death counts and GDP (or GDP per capita) by country/year.

Visualisations showing how death counts (or rates) change with GDP, and patterns by region or cause.

A modelling experiment (for example, regression or classification) showing how well GDP can predict death numbers/rates (with caveats).

Insights and reflections: What do the results suggest about the link between economic development and health outcomes? What limitations exist (data quality, confounders, model simplicity)?

Limitations & Considerations

Data quality may vary by country and year (reporting completeness, classification changes).

Correlation does not imply causation: GDP may be associated with death rates, but many other factors (health infrastructure, demographics, environmental risks, policy) matter.

Models used are simple (for demonstration) and may not capture complex causal relationships.

You may consider extending this work: include more variables (education, health expenditure, population demographics), use more advanced models, or explore cause-specific death rates rather than counts.

Potential Extensions

Include population data to compute death rates (deaths per 1000 or per 100 000 population) rather than raw counts.

Use GDP per capita or other economic indicators (health spending, inequality).

Time‐series modelling: how changes in GDP over time within a country relate to changes in death rates.

Geographic/region analysis: group countries by income-level or region and compare.

Advanced ML or statistical modelling: e.g., random forest, gradient boosting, panel data regression with fixed effects.


Acknowledgements:

The original dataset (e.g., from Kaggle or other source) that provides the annual cause-of-death numbers.

Any other datasets (GDP, population) used.

