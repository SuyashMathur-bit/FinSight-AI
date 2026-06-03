# FinSight AI

### AI-Powered Personal Finance Coach using Customer Segmentation, Expense Prediction, and Anomaly Detection

##  Project Overview

FinSight AI is an end-to-end Machine Learning project that analyzes personal financial behavior and provides meaningful insights using data-driven techniques.

The project combines customer segmentation, expense prediction, anomaly detection, and personalized financial recommendations to help users better understand and improve their financial health.

---

##  Dataset

**Source:** Kaggle Personal Finance Dataset

**Data Type:** Structured Financial Data

### Key Features

* Monthly Income
* Monthly Expenses
* Savings
* Loan Amount
* Credit Score

---

##  Tools & Technologies

### Programming Language

* Python

### Development Environment

* Jupyter Notebook

### Libraries

* Pandas
* NumPy
* Matplotlib
* Scikit-Learn

### Machine Learning Algorithms

* K-Means Clustering
* Random Forest Regression
* Isolation Forest

---

##  Data Preparation

### Data Cleaning

* Loaded and inspected the dataset
* Checked for missing values
* Verified feature consistency
* Removed unnecessary information

### Feature Engineering

Selected important financial attributes:

* Monthly Income
* Monthly Expenses
* Savings
* Loan Amount
* Credit Score

### Feature Scaling

Applied StandardScaler to normalize numerical features before machine learning model training.

---

##  Exploratory Data Analysis

Performed exploratory analysis to understand financial patterns and customer behavior.

### Visualizations

* Income Distribution
* Expense Distribution
* Savings Analysis
* Cluster Distribution
* Actual vs Predicted Expense Comparison
* Financial Anomaly Analysis

---

##  Machine Learning Workflow

### Phase 1: Customer Segmentation (K-Means Clustering)

Grouped users into different financial behavior categories.

Examples:

* High Income – High Savings
* Moderate Income – Moderate Savings
* High Spending Users

### Outputs

* Cluster Labels
* Cluster Distribution
* Cluster Analysis

---

### Phase 2: Expense Prediction (Random Forest Regression)

Built a predictive model to estimate monthly expenses using financial features.

### Model Configuration

* n_estimators = 300
* max_depth = 6
* min_samples_split = 10
* min_samples_leaf = 5

### Outputs

* Predicted Expenses
* Actual vs Predicted Comparison
* Model Performance Evaluation

---

### Phase 3: Financial Recommendation Engine

Generated personalized recommendations based on financial conditions.

Examples:

* Increase monthly savings
* Reduce unnecessary expenses
* Improve credit score
* Focus on debt reduction

---

### Phase 4: Financial Anomaly Detection (Isolation Forest)

Detected unusual financial profiles that significantly differ from normal user behavior.

Examples:

* Excessive spending patterns
* High debt profiles
* Unusual savings behavior

---

##  Key Visualizations

### Customer Segmentation

* Scatter Plot
* Cluster Distribution Chart

### Expense Prediction

* Actual vs Predicted Bar Graph

### Financial Analysis

* Income vs Expenses Analysis

### Anomaly Detection

* Normal vs Anomalous User Distribution

---

##  Key Insights

* Users naturally form distinct financial behavior groups.
* Spending habits vary significantly across clusters.
* Random Forest provides reliable expense predictions.
* Anomaly detection helps identify potentially risky financial profiles.
* Personalized recommendations improve financial awareness.

---

##  Business Impact

FinSight AI helps users:

* Understand spending habits
* Improve savings behavior
* Detect financial risks
* Make informed financial decisions
* Receive personalized financial guidance

---

##  Repository Structure

├── FinSight_AI.ipynb

└── README.md

---

##  Future Improvements

* Deep Learning-based Financial Forecasting
* Streamlit Web Application
* Real-Time Expense Tracking
* Investment Recommendation System
* AI Financial Chat Assistant

---

##  Author

### Suyash Mathur

Computer Science Student | AI & ML Enthusiast

Focused on building practical Machine Learning solutions and real-world AI applications.
