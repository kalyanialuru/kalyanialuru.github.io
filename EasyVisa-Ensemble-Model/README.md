# 🛂 EasyVisa – Visa Approval Prediction Using Ensemble Learning

**Objective:**  
Build a machine learning model to predict the likelihood of visa approval based on applicant data, using ensemble techniques for improved accuracy and generalization.

---

## 📊 Problem Statement

Visa processing is often resource-intensive and prone to delays. This project aims to automate the decision support process by predicting whether a visa application is likely to be approved or denied using historical application data.

---

## 🔍 Project Overview

- **Goal:** Predict visa approval status (Approved or Denied)
- **Dataset:** Structured dataset of anonymized visa application records with features such as applicant type, employment category, wage level, and job location
- **Target Variable:** Binary classification (`Approved`, `Denied`)

---

## 🧠 Machine Learning Approach

### 🔧 Data Preprocessing:
- EDA to understand data distribution and identify outliers
- One-hot encoding of categorical variables
- Handling class imbalance

### ⚙️ Modeling Techniques:
- **Baseline:** Logistic Regression
- **Advanced Models:** Bagging and Boosting
- **Final Model:** XGBoost Classifier
- **Hyperparameter Tuning:** GridSearchCV for max depth, learning rate, estimators

---

## ✅ Results

| Metric        | Value   |
|---------------|---------|
| Accuracy      | **75%** |
| F1 Score      | **82%** |
| Precision     | 80%     |
| Recall        | 84%     |

XGBoost provided strong performance with a high recall, helping to minimize false negatives (i.e., wrongly denied legitimate applications).

---

## 🛠️ Tools & Technologies

- **Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, XGBoost, matplotlib, seaborn
- **Techniques:** Ensemble Learning (Bagging & Boosting), Feature Engineering, Grid Search
