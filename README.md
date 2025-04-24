# ADMET LogS Modeling

This repository contains a Python script for performing **Exploratory Data Analysis (EDA)** and **Machine Learning modeling** on molecular datasets to predict aqueous solubility (LogS), an important ADMET property.

## 📁 Files

- `admet_logS_modeling.py` — Main script for EDA and modeling
- `plots/` — Folder where plots from EDA are saved
- `model_comparison.csv` — Summary of model performance (generated)

## 🔍 Features

- Cleans and loads input CSV
- Drops rows with missing values
- Visualizes LogS distribution and feature correlations
- Scales features using `StandardScaler`
- Trains and evaluates:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
- Saves model comparison metrics (MSE, R²)
