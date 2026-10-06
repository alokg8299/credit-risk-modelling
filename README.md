# Credit Risk Modelling Using Machine Learning

An end-to-end machine learning project for predicting whether a credit applicant represents a good or bad credit risk using demographic, financial, and loan-related features.

## Project Overview

This project develops a credit-risk classification framework using the German Credit dataset. The workflow includes exploratory data analysis, missing-value treatment, categorical encoding, class-imbalance handling, model training, hyperparameter tuning, and model evaluation.

## Key Steps

- Performed exploratory data analysis and identified missing-value patterns.
- Used pipeline-based imputation instead of dropping incomplete observations.
- Applied One-Hot Encoding to categorical variables.
- Used stratified train-test splitting to preserve class distribution.
- Addressed class imbalance using class-weighted models.
- Compared Logistic Regression, Decision Tree, Random Forest, Extra Trees, and XGBoost.
- Performed hyperparameter tuning using 5-fold Stratified Cross-Validation.
- Evaluated models using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
- Analyzed feature importance for model interpretation.

## Dataset

The German Credit dataset contains 1,000 customer records with demographic, financial, and loan-related characteristics.

**Target Variable:** `Risk`

- `good` – Good credit risk
- `bad` – Bad credit risk

## Technologies

Python | Pandas | NumPy | Scikit-learn | XGBoost | Matplotlib | Seaborn | Jupyter Notebook

## Project Workflow

Data Loading → EDA → Missing-Value Treatment → Encoding → Train-Test Split → Class-Imbalance Handling → Model Training → Hyperparameter Tuning → Evaluation → Feature Interpretation

## Conclusion

The project demonstrates an end-to-end approach to credit-risk prediction while addressing important real-world challenges such as missing data, class imbalance, categorical variables, and model interpretability.
