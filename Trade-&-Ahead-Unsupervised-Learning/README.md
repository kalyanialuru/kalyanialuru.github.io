# 📈 Trade & Ahead – Unsupervised Learning for Stock Clustering

## 🎯 Objective  
Use unsupervised learning techniques to cluster stocks based on financial performance indicators, helping investors diversify portfolios and mitigate risks.

---

## 📊 Problem Statement  
Investors often struggle to identify patterns across hundreds of stocks. This project leverages clustering techniques to segment stocks into meaningful groups based on shared characteristics, enabling better-informed investment strategies.

---

## 🔍 Project Overview  
- **Goal:** Cluster similar stocks using unsupervised learning methods  
- **Dataset:** Historical stock performance data including volatility, average return, market cap, P/E ratio, and other financial metrics  
- **Target Variable:** None (unsupervised learning task)

---

## 🧠 Machine Learning Approach  

### 🔧 Data Exploration & Preparation  
- Performed EDA to understand data structure and detect outliers  
- Normalized and scaled features to ensure fair clustering  
- Selected relevant financial indicators for clustering

### ⚙️ Clustering Techniques  
- **K-means Clustering:** Identified optimal number of clusters using the Elbow method  
- **Hierarchical Clustering:** Validated cluster consistency using dendrograms  
- Final model grouped stocks into **5 distinct clusters** with unique risk-return profiles

---

## ✅ Results  
- Stocks were successfully clustered into 5 groups based on performance traits  
- Helped reveal:
  - Defensive vs. high-risk stocks  
  - Undervalued opportunities  
  - Sector and volatility-based segmentation  
- Findings supported **portfolio diversification strategies**

---

## 🛠️ Tools & Technologies  
- Language: Python  
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `scipy`  
- Techniques: K-means Clustering, Hierarchical Clustering, EDA, Feature Scaling
