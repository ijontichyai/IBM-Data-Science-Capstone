# IBM Data Science Capstone Project

## Predicting Falcon 9 First-Stage Landings 🚀

This repository contains my final project for the **IBM Applied Data Science Capstone**, part of the **IBM Data Science Professional Certificate**.

The project investigates whether historical SpaceX Falcon 9 launch data can be used to predict the successful landing of the first stage.

## Project Objective

The objective is to build an end-to-end data science pipeline that answers the following question:

**Given launch conditions and historical outcomes, will the Falcon 9 first stage land successfully?**

## Project Workflow

The analysis includes:

* Data collection using the **SpaceX REST API**
* Web scraping of Falcon 9 launch records
* Data cleaning and feature engineering
* Exploratory Data Analysis using **Pandas, Matplotlib, and Seaborn**
* SQL-based exploratory analysis
* Interactive launch-site mapping using **Folium**
* Interactive dashboard development using **Plotly Dash**
* Machine learning classification and hyperparameter tuning using **GridSearchCV**

## Machine Learning Models

The following classification algorithms were evaluated:

* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree
* K-Nearest Neighbors (KNN)

### Final Results

* **Launch records analyzed:** 90
* **Best cross-validation accuracy:** 84.8%
* **Verified holdout accuracy:** 83.3%
* **Best validation model:** Support Vector Machine
* Logistic Regression and SVM both achieved **83.3% test accuracy**

The analysis also showed that the most important operational error was **false positives — predicting a successful landing when the booster actually failed to land**.

## Key Findings

* Launch site, payload, orbit, booster configuration, and flight history influence landing outcomes.
* **KSC LC-39A** achieved a success rate of approximately **76.9%**.
* Landing success generally improved as SpaceX accumulated flight experience.
* Coastal launch-site locations provide operational advantages including transportation access, safety separation, and open-ocean launch corridors.
* Predictive models can provide useful decision support, but should not be treated as autonomous go/no-go systems.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* BeautifulSoup
* SQL
* Folium
* Plotly
* Dash
* Scikit-learn
* Jupyter Notebook

## Repository Contents

This repository contains:

* SpaceX API data collection notebook
* Web scraping notebook
* Data wrangling notebook
* Exploratory Data Analysis notebooks
* SQL analysis
* Folium launch-site analysis
* Plotly Dash application
* Machine learning classification notebook
* Data files used throughout the project
* Final project presentation/report

## Author

**Armando Romero Mariscal Guasp**

IBM Data Science Professional Certificate
Applied Data Science Capstone — 2026
