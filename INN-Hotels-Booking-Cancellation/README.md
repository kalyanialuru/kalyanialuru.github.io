
# 🏨 INN Hotels – Booking Cancellation Prediction

## 🎯 Objective  
Build a predictive model to identify the likelihood of booking cancellations, enabling INN Hotels to take proactive steps in managing refunds and optimizing occupancy.

---

## 📊 Problem Statement  
Booking cancellations significantly affect hotel revenue and resource planning. This project aims to develop a predictive model that flags likely cancellations ahead of time, allowing the hotel to optimize room allocations and improve refund policies.

---

## 🔍 Project Overview  
- **Goal:** Predict whether a booking will be canceled  
- **Dataset:** Structured booking records with features such as booking date, room type, stay duration, deposit type, and customer demographics  
- **Target Variable:** Binary classification – `Canceled` or `Not Canceled`

---

## 🧠 Machine Learning Approach  

### 🔧 Data Preparation  
- Performed exploratory data analysis (EDA) to understand trends and correlations  
- Handled missing values and encoded categorical variables  
- Balanced the dataset if necessary to avoid bias

### ⚙️ Modeling Techniques  
- **Baseline Model:** Logistic Regression  
- **Advanced Model:** Decision Tree Classifier  
- **Optimization:** Post-pruning to reduce overfitting  
- **Evaluation Metrics:** Accuracy, Precision, Recall, AUC-ROC Curve

---

## ✅ Results  

| Metric     | Value  |
|------------|--------|
| Accuracy   | 87%    |
| Precision  | 85%    |
| Recall     | 88%    |
| AUC-ROC    | 0.90   |

- The **post-pruned Decision Tree model** achieved strong accuracy and recall  
- Model provided clear decision rules, improving interpretability and trust for stakeholders

---

## 🛠️ Tools & Technologies  
- Language: Python  
- Libraries: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`  
- Techniques: Logistic Regression, Decision Trees, Pruning, AUC-ROC Analysis
