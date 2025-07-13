# 🌀 ReneWind – Predictive Maintenance for Wind Turbines

**Objective:**  
Develop a machine learning pipeline to predict machinery failures in wind turbines, enabling proactive maintenance and reducing downtime and operational costs.

---

## 📊 Problem Statement

Wind energy companies often face unplanned turbine failures, leading to significant losses due to repair costs and production halts. By predicting failures in advance, we can proactively schedule maintenance and optimize resource allocation.

---

## 🔍 Project Overview

- **Goal:** Predict turbine component failures using labeled sensor data.
- **Dataset:** Simulated wind turbine dataset with features like temperature, vibration, pressure, and RPM readings.
- **Target:** Binary classification (Failure = 1 / No Failure = 0)

---

## 🧠 Machine Learning Approach

### 🔧 Data Preprocessing:
- Missing value handling
- Outlier detection and removal
- Feature scaling and encoding

### ⚙️ Modeling Techniques:
- **Class Balancing:** Up-sampling minority class and down-sampling majority class
- **Modeling Algorithm:** Random Forest Classifier
- **Hyperparameter Tuning:** GridSearchCV
- **Regularization:** Controlled overfitting using depth and leaf size constraints

---

## ✅ Results

| Metric        | Value   |
|---------------|---------|
| Accuracy      | **94%** |
| Recall        | **88%** |
| Precision     | 90%     |
| F1 Score      | 89%     |
| AUC-ROC       | 0.93    |

The tuned model significantly improved recall, minimizing false negatives and reducing the risk of undetected failures.

---

## 🖥️ Tools & Technologies

- **Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn
- **Techniques:** Sampling, Random Forest, GridSearchCV, Evaluation Metrics

---

## 📁 Folder Structure

