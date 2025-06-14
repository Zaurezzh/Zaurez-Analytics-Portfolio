# 🧠 Customer Churn Prediction Model (Python + ML)

This predictive analytics project uses Python to identify customers most likely to churn using the Telco Customer Churn dataset. The project demonstrates end-to-end machine learning workflow—from preprocessing and exploratory data analysis to model training and explainability using SHAP. Designed for both business impact and portfolio showcasing.


---

## 🌐 Project Overview
- **Tool**: Python (Jupyter Notebook / Google Colab)  
- **Dataset**: Telco Customer Churn [Kaggle Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Objective**: Predict churn using classification algorithms and explainable AI techniques (SHAP, feature importance)

---

## 📊 Key Features

### ✅ Data Cleaning & Processing
- Imputed missing values (TotalCharges) and corrected data types
- Performed one-hot encoding and feature standardization
- Addressed class imbalance using SMOTE (Synthetic Minority Oversampling Technique)

### 🔍 Exploratory Data Analysis (EDA)
- Churn vs Non-Churn distributions
- Correlation matrix and heatmap
- Boxplots for tenure, MonthlyCharges, etc.  
- Statistical analysis (e.g., chi-square, ANOVA)

### 🧠 Machine Learning Models
- **Logistic Regression**: Baseline interpretable model  
- **Random Forest**: Ensemble learning with feature importance  
- **XGBoost**: Boosted tree model with high predictive performance  
- Stratified train-test split with 70/30 ratio

### 📈 Evaluation Metrics
- Accuracy, Precision, Recall, F1-score  
- Confusion Matrix  
- ROC-AUC comparison for all models  


### 🔍 Feature Importance & Explainability
- Feature importance from Random Forest  
- **SHAP summary plot** for XGBoost  
- Optional SHAP **force plots** for individual churn explanation

### ⚖️ Fairness & Subgroup Performance
- Performance breakdown by `SeniorCitizen`, `Gender`, etc.  
- Recall/precision analysis for bias detection


---

## 📄 Project Preview

### 🔹 SHAP Summary Plot

![SHAP Summary](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Assets/SHAP%20Summary%20Plot.PNG)

### 🔹 Confusion Matrix - Random Forest

![Confusion Matrix - RF](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Assets/Confusion%20Matrix-RF.PNG)

### 🔹 Confusion Matrix - Log Reg

![Confusion Matrix - LR](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Assets/Confusion%20Matrix-LR.PNG)

### 🔹 Confusion Matrix - XG

![Confusion Matrix - XG](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Assets/Confusion%20Matrix-XG.PNG)

### 🔹 ROC Curve

![ROC Comparison](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Assets/ROC%20Curve.PNG)

---
### 🧠 Skills Demonstrated

- End-to-end ML pipeline (EDA → Modeling → Explainability)
SMOTE for imbalanced classification
- Model evaluation and ROC-AUC comparison
- SHAP for explainable AI (XGBoost + Local/Global explainability)
- Subgroup analysis and fairness metrics

---

## 🏠 Use Case
**Ideal for:**
- Data scientists building end-to-end ML pipelines  
- Analysts presenting churn risk to business stakeholders

---

### 📥 Download Notebook
[📘 Telco_Customer_Churn.ipynb](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Predictive_Modeling/Customer_Churn_XGBoost/Telco_Customer_Churn.ipynb)

---

## 🎓 Author
**Zaurez Hamid**  
[LinkedIn](https://www.linkedin.com/in/zaurez-h/) | [GitHub](https://github.com/Zaurezzh)

---

## ✈️ Contact & Feedback
Feel free to reach out for feedback, collaboration, or questions!
