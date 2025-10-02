# 🏦 Predicting Bank Term Deposit Subscriptions (Logistic Regression)

This project focuses on predicting whether a customer will subscribe to a **bank term deposit** using a **Logistic Regression** model.  
It demonstrates exploratory data analysis, feature encoding, model building, evaluation, and insights for data-driven marketing strategies.

## 🔹 Project Overview
- **Dataset:** 4,000+ customer records with 17+ attributes (demographics, campaign interactions, account info).
- **Exploratory Data Analysis (EDA):**
  - Handled missing values and outliers
  - Feature encoding for categorical variables
  - Identified correlations and trends
- **Modeling:**
  - Built a Logistic Regression classifier
  - Evaluated model using:
    - Accuracy = **98.45%**
    - ROC-AUC = **0.87**
    - Confusion matrix and ROC curve visualizations
- **Insights:**
  - Interpreted model coefficients to identify high-impact features
  - Features driving subscriptions help optimize targeted marketing strategies

## 🛠️ Tech Stack
- Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- Jupyter Notebook

## 📂 Dataset
The dataset contains customer demographics and banking campaign information.  
If using publicly available data (e.g., UCI Bank Marketing dataset), include link:  
[Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

```bash
data/bank_term_deposit.csv
