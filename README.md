[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Zafarebad/Predicting-Bulldozer-Prices-Using-Machine-Learning/blob/main/your_notebook.ipynb)


# Predicting-Bulldozer-Prices-Using-Machine-Learning

This project is focused on building a regression model to predict the sale price of bulldozers using historical data. It is based on the **Bluebook for Bulldozers** dataset from Kaggle.

The notebook walks through an **end-to-end machine learning workflow**, including data exploration, preprocessing, model building, evaluation, and export.

---

## 📌 Problem Statement

> Predict the **sale price** of a bulldozer given its specifications and usage history.

This is a supervised regression task using tabular structured data. The target variable is `SalePrice`.

---

## 📊 Dataset

- **Source**: [Kaggle - Bluebook for Bulldozers](https://www.kaggle.com/competitions/bluebook-for-bulldozers)
- **Files Used**:
  - `Train.csv`
  - `Valid.csv`
  - `Test.csv`
  - `Data Dictionary.xlsx`

The dataset contains various features like year made, model ID, usage hours, etc.

---

## 🧠 Machine Learning Approach

- **Model Used**: `RandomForestRegressor` from scikit-learn
- **Evaluation Metric**: RMSLE (Root Mean Squared Log Error)
- **Techniques Applied**:
  - Handling missing values
  - Feature engineering
  - Parsing dates
  - Pipeline creation
  - Model tuning and validation

---

## 📈 Results

The final model achieves a **reasonable RMSLE score** on the validation set and performs well on unseen test data. The approach is modular, allowing for future improvements and hyperparameter tuning.

---
