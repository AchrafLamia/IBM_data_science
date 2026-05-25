# SpaceX Falcon 9 First-Stage Landing Prediction

IBM Data Science Professional Certificate — Capstone Project

---

## Overview

This project applies the full data science workflow to predict whether the SpaceX Falcon 9 rocket's first stage will land successfully after launch. Because reusability of the first stage is the primary cost driver, an accurate landing prediction allows third parties to estimate launch cost and compete with SpaceX on bids.

## Objective

Build a binary classification model that predicts first-stage landing success using historical launch data collected from the SpaceX REST API and Wikipedia.

## Methodology

1. **Data Collection** — Query the SpaceX REST API for launch records; supplement with Wikipedia web scraping.
2. **Data Wrangling** — Clean missing values, encode categorical variables, and engineer features.
3. **Exploratory Data Analysis** — Investigate patterns using SQL queries and statistical visualizations.
4. **Interactive Visual Analytics** — Map launch sites and outcomes with Folium; build a Plotly Dash dashboard.
5. **Predictive Modeling** — Train and tune Logistic Regression, Decision Tree, SVM, and K-Nearest Neighbors classifiers; select the best model by test accuracy.

## Tech Stack

| Category | Tools |
|---|---|
| Language | Python 3 |
| Data manipulation | Pandas, NumPy |
| Database queries | SQL (SQLite) |
| Machine learning | Scikit-learn |
| Geospatial visualization | Folium |
| Interactive dashboard | Plotly Dash |
| Web scraping | BeautifulSoup, Requests |
| Presentation | Jupyter Notebook, PDF |

## Repository Contents

| File | Description |
|---|---|
| `jupyter-labs-spacex-data-collection-api.ipynb` | Fetch launch records from the SpaceX REST API |
| `jupyter-labs-webscraping.ipynb` | Scrape Falcon 9 launch history from Wikipedia |
| `labs-jupyter-spacex-Data wrangling.ipynb` | Clean data, handle missing values, encode features |
| `jupyter-labs-eda-sql-coursera_sqllite.ipynb` | Exploratory data analysis using SQL on a SQLite database |
| `notebook_Exploratory_Data_Analysis_with_Visualisation_Lab_jJkKVG6F1.ipynb` | Statistical EDA with Matplotlib and Seaborn |
| `notebook_Interactive_Visual_Analytics_with_Folium_M8uUhCmHY.ipynb` | Interactive launch-site maps using Folium |
| `notebook_Predictive_Analysis_-_Machine_Learning_Lab_hdUi_lnX5.ipynb` | Train, tune, and evaluate classification models |
| `spacex_dash_app.py` | Plotly Dash app for interactive launch analytics |
| `SpaceX_compressed.pdf` | Final project presentation slides |

## Key Findings

- Launch success rate increased significantly over time as SpaceX refined operations.
- Launch site, orbit type, and payload mass are the strongest predictors of landing success.
- The **Decision Tree classifier** (with GridSearchCV tuning) achieved the highest test accuracy among the evaluated models, making it the recommended model for deployment.

## Certificate

[IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) — Coursera / IBM
