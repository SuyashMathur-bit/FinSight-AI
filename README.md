# 💰 FinSight AI – Intelligent Personal Finance & Income Prediction System

[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange.svg)](https://scikit-learn.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

An AI-powered Personal Finance Analytics platform that predicts monthly income, analyzes financial behavior, evaluates model performance, and performs comprehensive machine learning error analysis using Random Forest Regression.

---

## 📖 Overview

**FinSight AI** is an end-to-end Machine Learning project developed to predict an individual's monthly income based on financial attributes such as monthly expenses, savings, loan amount, and credit score.

The project demonstrates a complete machine learning workflow including data preprocessing, feature engineering, K-Means customer segmentation, model training with an 80/20 train-test split, performance evaluation ($R^2$, RMSE, MAE), bias-variance analysis, feature importance ranking, and residual error analysis following Andrew Ng's Machine Learning best practices.

---

## ✨ Key Features

### 🤖 Machine Learning & Modeling
- **Supervised Learning:** Random Forest Regression for monthly income forecasting.
- **Unsupervised Learning:** K-Means Clustering for financial profile segmentation.
- **Anomaly Detection:** Isolation Forests to detect unusual expense-to-income behaviors.
- **Automated Advisory:** Rule-based financial recommendation engine based on expense-to-income and debt thresholds.

### 📊 Performance & Diagnostics
- **Evaluation Metrics:** Evaluated using RMSE, MAE, MSE, and $R^2$ Score.
- **Bias-Variance Diagnosis:** Explicit training vs. testing $R^2$ evaluation with a minimal generalization gap.
- **Residual Error Analysis:** Actual vs. Predicted scatter analysis, error distribution histogram, and percentage error profiling.
- **Feature Importance:** Identifies the primary drivers behind income estimation (Monthly Expenses, Savings, Credit Score, Loan Amount).

---

## 📈 Model Performance

| Metric | Score | Note |
|---|---|---|
| **Testing $R^2$** | ~0.80 - 0.81 | Strong variance explanation on unseen test data |
| **Training $R^2$** | ~0.81 - 0.82 | Minimal generalization gap (< 0.01, no overfitting) |
| **RMSE** | ~$840 - $870 | Low root mean squared error relative to income spread |
| **MAE** | ~$650 - $670 | Mean absolute error |

---

## 📂 Dataset & Reproducibility

* **Source:** [Personal Finance ML Dataset (Kaggle)](https://www.kaggle.com/datasets/arfree/personal-finance-ml-dataset) (by Arif Miah)
* **Records:** 32,424 structured financial records
* **File:** `synthetic_personal_finance_dataset.csv` (included directly in this repository)
* **Key Features:**
  - `monthly_expenses_usd`: Monthly recurring and variable expenses
  - `savings_usd`: Total savings balance
  - `loan_amount_usd`: Outstanding loan balance
  - `credit_score`: Credit score (300–850)
  - `monthly_income_usd`: Target variable

---

## 🛠 Tech Stack

| Category | Technology |
|---|---|
| **Language** | Python 3 |
| **Environment** | Jupyter Notebook |
| **Data Analysis** | Pandas, NumPy |
| **Machine Learning** | Scikit-Learn (Random Forest, KMeans, Isolation Forest) |
| **Visualization** | Matplotlib |
| **Version Control** | Git & GitHub |

---

## 🚀 How to Run Locally

### 1. Clone Repository
```bash
git clone https://github.com/SuyashMathur-bit/FinSight-AI.git
cd FinSight-AI
```

### 2. Install Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib
```

### 3. Launch Notebook
```bash
jupyter notebook "FinSight AI.ipynb"
```
Run all cells. The dataset is loaded via relative path `synthetic_personal_finance_dataset.csv` and will execute immediately.

---

## 🔄 Machine Learning Workflow

```
Financial Dataset (32,424 rows)
        │
        ▼
Data Preprocessing & EDA
        │
        ▼
Train-Test Split (80% Train / 20% Test)
        │
        ▼
Random Forest Regressor (300 estimators, max_depth=6)
        │
        ▼
Evaluation Metrics (RMSE, MAE, R²)
        │
        ▼
Residual Error Analysis & Distribution
        │
        ▼
Bias-Variance Generalization Check
        │
        ▼
Feature Importance & Recommendations
```

---

## 👤 Author

* **Suyash Mathur** - [SuyashMathur-bit](https://github.com/SuyashMathur-bit)
