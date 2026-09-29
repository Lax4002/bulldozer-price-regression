# Bulldozer Sale Price Regression

End-to-end machine-learning regression project for predicting bulldozer auction prices from historical sales and equipment attributes.

## Problem
Estimate future sale prices from structured tabular data while handling missing values, categorical variables and time-dependent features.

## Approach
- Exploratory data analysis and preprocessing.
- Date feature engineering.
- Missing-value handling and categorical encoding.
- Random Forest regression.
- Validation using RMSLE, the metric used by the Kaggle Bluebook for Bulldozers competition.
- Hyperparameter experimentation and feature-importance analysis.

## Stack
Python, Pandas, NumPy, Matplotlib, Scikit-learn.

## Repository contents
- `bulldozer-price-regression.ipynb` — full modelling workflow.
- `requirements.txt` — dependencies.

## Data
The original Bluebook for Bulldozers dataset is not committed because of size. Download it from the Kaggle competition and place the required CSV files inside a local `data/` directory.

## Note
This is a portfolio learning project built around a public Kaggle dataset and demonstrates a complete tabular ML workflow.
