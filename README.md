# 🏆 AI-ML Competition - E-Commerce Customer Purchase Prediction

## 📌 Repository Overview

Welcome to my **AI-ML Competition Repository**! 🚀 This project focuses on **predicting customer purchases** using **machine learning techniques**. The goal is to analyze customer data, apply feature engineering, and train an **AI model** to forecast whether a customer will make their next purchase.

This repository includes **data preprocessing, model training, evaluation, and key insights** for improving customer targeting strategies. 📊

---

## 🔬 1. Methodology

### 📌 Data Preprocessing
- 🛠️ **Handling missing values** in `Annual_Income` by imputing median values.
- 📆 **Transforming Birth_Year** into `Age` for better feature representation.
- 🏷️ **Encoding categorical variables** (`Education Level`, `Family Status`) using **One-Hot Encoding**.
- 📏 **Normalizing numerical features** for consistent scaling.
- 📂 **Splitting dataset**: **80% Training / 20% Validation**.

---

## 🤖 2. Model & Performance Metrics

A **Random Forest Classifier** was trained to predict customer purchases.

### 📊 Performance Metrics
✅ **Accuracy**: **86.14%** 🎯  
✅ **F1-Score**: **0.53** (indicating room for improvement in predicting buyers)  
✅ **Precision & Recall**: The model performs well for **non-buyers**, but struggles with **buyers**.  

### 🔍 Confusion Matrix
- The model correctly identifies most **non-buyers**, but has a higher **false negative rate** for **buyers**.

### 📈 ROC Curve & AUC Score
- **ROC Curve** demonstrates the model’s class distinction ability.
- **AUC Score** suggests **moderate** performance, requiring further improvements.

### 💡 Feature Importance
- **Key factors influencing purchases**:
  - Spending habits 💰
  - Promotional campaigns 🎯
  - Past purchases 🛍️

---

## 📊 3. Business Insights & Recommendations

### 🔍 Key Insights
- 📌 **Customers with prior purchases** are more likely to buy again.
- 🏷️ **Promotional campaigns** play a major role in repeat purchases.
- 💰 **High-income customers** tend to purchase **more frequently**.
- ❗ **The model struggles with rare buyers (Class 1)** → Need for **data balancing**.

### 📌 Recommendations
⚖️ **Balance dataset** using **SMOTE** to improve prediction for rare buyers.  
🛠️ **Hyperparameter tuning** (adjust `n_estimators`, `max_depth`) to enhance performance.  
🚀 **Explore alternative models** like **XGBoost** or **Neural Networks** for better accuracy.  
🎯 **Optimize marketing campaigns** by targeting customers **more likely** to purchase.  

---

## 🏆 Final Thoughts

This **predictive model** provides **valuable insights** to enhance **marketing strategies** and **boost customer engagement**. By implementing the suggested improvements, the model can achieve **higher accuracy, better F1-scores**, and **more effective business decisions**. 🚀

🔗 **Follow this repository for updates and improvements in AI-ML predictions!** 🎯
