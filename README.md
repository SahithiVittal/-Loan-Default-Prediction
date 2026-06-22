# Loan Default Prediction

## Project Overview
Developed machine learning models to predict loan default risk using customer demographic and financial attributes. The project aims to help financial institutions identify high-risk borrowers and support data-driven lending decisions.

---

## Business Problem
Incorrect assessment of borrower risk can lead to increased loan defaults and financial losses. This project focuses on predicting whether a customer will default on a loan based on their financial profile.

---

## Dataset
Features include:

- Age
- Income
- Employment Experience
- Home Ownership
- Loan Amount
- Loan Intent
- Interest Rate
- Credit History Length
- Credit Score
- Previous Loan Defaults

Target Variable:

- `loan_status`
    - 0 : Non-default
    - 1 : Default

---

## Project Workflow

### Data Preprocessing
- Handled missing values
- Removed duplicates
- Performed exploratory data analysis
- Encoded categorical variables
- Created new features:
  - Loan-to-Income Ratio
  - Debt-to-Income Ratio
  - Income Group
  - Previous Default Flag

### Statistical Analysis
- Chi-Square Test for categorical variables
- Mann-Whitney U Test for numerical variables

### Models Developed
1. Logistic Regression
2. Random Forest
3. XGBoost

---

## Model Performance

| Model | Accuracy | Precision | Recall | F1-score |
|---------|----------|----------|--------|---------|
| Logistic Regression | 0.85 | 0.71 | 0.47 | 0.57 |
| Random Forest | 0.93 | 0.89 | 0.74 | 0.81 |
| XGBoost | 0.93 | 0.90 | 0.77 | 0.82 |

---

## Key Insights
- Previous loan defaults strongly influence future defaults.
- Higher loan-to-income ratios are associated with increased default risk.
- Credit score is one of the most important predictors.
- Random Forest and XGBoost outperform Logistic Regression.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SciPy

---


