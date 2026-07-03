# Parkinson's Disease - Binary Classification

## Project Purpose

This student project explores a reproducible machine learning workflow for binary classification of Parkinson's disease. The goal is to demonstrate data preparation, model building, evaluation, and comparison of several classification algorithms using a tabular clinical/biomedical dataset (see the notebook for dataset source and details).

## Objectives

- Implement end-to-end preprocessing and feature engineering steps.
- Train and compare multiple classification models.
- Use cross-validation and hyperparameter tuning to select a robust model.
- Evaluate models with appropriate metrics and visualizations.

## Topics Covered

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing (scaling, encoding, imputation as needed)
- Feature selection and/or feature engineering
- Model training, validation and selection
- Model evaluation using classification metrics and visual tools
- Reproducible experimentation with fixed random seeds and documented steps

## Techniques & Algorithms

Typical techniques used in the accompanying notebook include:

- Data preprocessing: `pandas`, `numpy`, `scikit-learn` transformers
- Feature scaling: standardization or normalization
- Cross-validation and model selection: `GridSearchCV`/`cross_val_score`
- Models evaluated: Logistic Regression, Decision Trees, Random Forests, Support Vector Machines, Gradient Boosting/XGBoost
- Evaluation metrics: accuracy, precision, recall, F1-score, confusion matrix

## Notebook

See the main analysis and runnable code in the notebook: [parkinsons_disease_binary_classification.ipynb](parkinsons_disease_binary_classification.ipynb).
