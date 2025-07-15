
# 🔄 ReCell – Dynamic Pricing for Refurbished Gadgets

## 🎯 Objective  
Develop a regression-based pricing model to predict the market value of refurbished electronic devices, helping optimize pricing strategy and maximize profitability.

---

## 📊 Problem Statement  
Pricing refurbished gadgets accurately is crucial for maintaining competitiveness and profitability. This project builds a predictive model that estimates the price of used devices based on key features such as device type, condition, brand, and age.

---

## 🔍 Project Overview  
- **Goal:** Predict the selling price of a refurbished gadget  
- **Dataset:** Historical pricing data of used devices with features like brand, storage capacity, age, cosmetic condition, and warranty status  
- **Target Variable:** Continuous variable – `Price`

---

## 🧠 Machine Learning Approach  

### 🔧 Data Preparation  
- Cleaned and transformed raw data  
- Handled missing values and standardized numeric features  
- Encoded categorical features using one-hot encoding

### ⚙️ Modeling Techniques  
- **Model Used:** Linear Regression  
- **Evaluation Metric:** R-squared  
- **Feature Engineering:** Identified and ranked features influencing pricing

---

## ✅ Results  

| Metric    | Value |
|-----------|-------|
| R² Score  | 0.84  |

- The model explained **84% of variance** in pricing  
- Key drivers included device condition, brand, and age

---

## 🛠️ Tools & Technologies  
- Language: Python  
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`  
- Techniques: Linear Regression, Data Preprocessing, Feature Engineering
