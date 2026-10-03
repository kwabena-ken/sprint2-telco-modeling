# Sprint 2 — Telco modeling basics

Trained a churn classifier and a small bill regression on the IBM Telco Customer Churn data.

## What is in this repo
- `sprint2_modeling.ipynb` — split, encoding, scaling, models, scores, and charts

## Classification
- Target: Churn (Yes/No)
- 80/20 stratified split, random_state=42
- Logistic regression after one-hot encoding and standard scaling
- Test accuracy about 0.806, versus 0.735 for always guessing No
- 5-fold accuracy mean about 0.804
- Yes precision about 0.66, Yes recall about 0.56, Yes F1 about 0.60

## Regression
- Target: MonthlyCharges
- RMSE about 1.05
- Tight because TotalCharges already contains the bill

## How to run
Open the notebook in Google Colab and run the cells from top to bottom.
