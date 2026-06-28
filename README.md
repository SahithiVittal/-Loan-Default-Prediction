# Loan Default Risk Analytics

## Project Overview

Financial institutions face significant risks due to loan defaults. This project develops a machine learning solution to predict whether a borrower is likely to default on a loan based on demographic, financial, and credit-related information.

The project covers the complete machine learning lifecycle, including exploratory data analysis, statistical testing, feature engineering, data preprocessing, model development, evaluation, and business recommendations.

---

## Business Problem

Loan defaults result in financial losses for banks and lending institutions. The objective of this project is to build a predictive model that can accurately identify high-risk borrowers, enabling lenders to make informed loan approval decisions and reduce credit risk.

---

## Dataset

The dataset contains borrower demographic, financial, and credit history information.

**Target Variable**

- `loan_status`
  - **0** → Non-Default
  - **1** → Default

### Key Features

- Age
- Gender
- Education
- Annual Income
- Employment Experience
- Home Ownership
- Loan Amount
- Loan Intent
- Interest Rate
- Loan-to-Income Ratio
- Credit History Length
- Credit Score
- Previous Loan Default

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SciPy
- Jupyter Notebook

---

## Project Workflow

1. Data Loading
2. Data Overview
3. Data Quality Assessment
4. Exploratory Data Analysis
5. Statistical Testing
6. Feature Engineering
7. Data Preprocessing
8. Model Building
9. Model Evaluation
10. Feature Importance
11. Business Recommendations

---

## Exploratory Data Analysis

The dataset was analyzed to understand:

- Loan default distribution
- Numerical feature distributions
- Categorical feature distributions
- Relationship between features and loan default
- Feature correlations

---

## Statistical Analysis

The following statistical tests were performed:

- Mann–Whitney U Test (Numerical Features)
- Chi-Square Test (Categorical Features)

These tests helped identify statistically significant variables associated with loan default.

---

## Feature Engineering

Engineered features include:

- Income Group
- Credit Score Category
- Employment Experience Group

These features improve model interpretability and predictive performance.

---

## Machine Learning Models

The following models were developed and compared:

- Logistic Regression (Baseline)
- Decision Tree
- Random Forest
- XGBoost

---

## Model Performance

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|-------|---------:|----------:|--------:|---------:|---------:|
| Logistic Regression | 88.60% | 88.39% | 74.27% | 80.72% | 96.22% |
| Decision Tree | 89.22% | 86.06% | 78.84% | 82.29% | 86.54% |
| Random Forest | 90.88% | 94.73% | 78.84% | 86.06% | 97.63% |
| **XGBoost** | **91.79%** | **95.26%** | **78.98%** | **86.36%** | **98.17%** |

---

## Best Model

XGBoost achieved the best overall performance.

**Performance**

- Accuracy: **91.79%**
- Precision: **95.26%**
- Recall: **78.98%**
- F1-Score: **86.36%**
- ROC-AUC: **98.17%**

---

## Feature Importance

The XGBoost model identified the following features as the most influential:

- Previous Loan Defaults
- Loan-to-Income Ratio
- Home Ownership
- Loan Intent
- Interest Rate
- Annual Income

---

## Business Recommendations

- Perform additional verification for applicants with previous loan defaults.
- Closely monitor borrowers with high loan-to-income ratios.
- Incorporate credit history and interest rates into risk assessment.
- Use predictive models to support loan approval decisions and reduce default risk.

---

## Repository Structure

```
Loan_Default_Risk_Analytics/
│
├── data/
├── notebook/
├── images/
├── README.md
└── requirements.txt
```

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Cross-validation for robust model evaluation
- Model deployment using Streamlit or Flask
- Explainability using SHAP values
- Real-time loan default prediction API

---

## Author

**Sahithi Vittal**

- LinkedIn: *(Add your LinkedIn profile)*
- GitHub: *(Add your GitHub profile)*
