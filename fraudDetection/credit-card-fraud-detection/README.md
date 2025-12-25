# Credit Card Fraud Detection (LightGBM | Finance-Grade Project)

## 📌 Project Overview
Built a fraud detection machine learning pipeline to identify fraudulent transactions while minimizing false positives. The model is designed similar to real-world financial systems such as American Express, where business priority is:
- Catch maximum frauds (high recall)
- Avoid blocking genuine users (low false positives)

---

## 🗂 Dataset
Kaggle Credit Card Fraud Dataset  
Transactions: ~284,000  
Fraud Ratio: ~0.17% (heavily imbalanced dataset)

---

## 🎯 Objective
✔ Detect fraudulent transactions  
✔ Handle class imbalance effectively  
✔ Optimize Recall vs False Positive Rate  
✔ Provide explainability for financial trust & compliance  

---

## 🧠 Approach
1️⃣ Data Preprocessing  
2️⃣ Train-Test Split with Stratification  
3️⃣ Class Imbalance Handling using LightGBM weighting  
4️⃣ Model Training  
   - Baseline: Logistic Regression / Random Forest (for comparison)
   - Final Model: LightGBM

5️⃣ Model Evaluation
- Recall (Fraud Detection Strength)
- False Positive Rate
- ROC-AUC
- Precision-Recall Curve
- Confusion Matrix Heatmap

---

## 🔍 Explainability (Finance Requirement)
Used **SHAP Explainability** to interpret model predictions.
This helps financial teams understand:
- why a transaction is marked fraud
- which features influence decisions

---

## 🚀 Results
- Achieved high fraud recall
- Reduced false positives vs baseline models
- Realistic performance aligned to banking use-cases

---

## 🛠 Tech Stack
Python  
Pandas, NumPy  
Scikit-Learn  
LightGBM  
Matplotlib / Seaborn  
SHAP

---

## 🏦 Business Relevance
Used in:
Banking • Credit Cards • Payment Gateways • FinTech Platforms

This project aligns strongly with fraud analytics workflows.

---
## Background (Optional Reading)
This project is based on the Credit Card Fraud dataset from a collaboration between Worldline & ML Group.
Dataset size: 284,807 transactions | Fraud cases: 492 (0.172%)


## 👤 Author
Aditya Shivhare
