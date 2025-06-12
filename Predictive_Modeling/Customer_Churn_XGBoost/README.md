# 🧠 Customer Churn Prediction Model (Python + ML)

This machine learning project uses Python to predict customer churn using the Telco dataset. The model identifies which customers are likely to leave, based on demographics, account details, and service usage. This predictive analytics case study is ideal for advanced portfolio showcases and executive-level churn mitigation planning.

---

## 🌐 Project Overview
- **Tool**: Python (Jupyter Notebook / Google Colab)  
- **Dataset**: Telco Customer Churn [Kaggle Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Objective**: Predict churn using classification algorithms and explainable AI techniques (SHAP, feature importance)

---

## 📊 Key Features

### ✅ Data Cleaning & Processing
- Handled missing values (`TotalCharges`) and converted data types  
- One-hot encoded categorical columns and standardized numerical features  
- Class imbalance addressed using **SMOTE**

### 🔍 Exploratory Data Analysis (EDA)
- Distribution analysis of churn vs non-churn  
- Correlation heatmap  
- Boxplots for tenure, MonthlyCharges, etc.  
- Statistical analysis (e.g., chi-square, ANOVA — optional extension)

### 🧠 Machine Learning Models
- **Logistic Regression**: Baseline interpretable model  
- **Random Forest**: Ensemble learning with feature importance  
- **XGBoost**: Boosted tree model with high predictive performance  
- Stratified train-test split with 70/30 ratio

### 📈 Evaluation Metrics
- Accuracy, Precision, Recall, F1-score  
- Confusion Matrix  
- ROC-AUC comparison for all models  
- GridSearchCV tuning (optional)

### 🔍 Feature Importance & Explainability
- Feature importance from Random Forest  
- **SHAP summary plot** for XGBoost  
- Optional SHAP **force plots** for individual churn explanation

### ⚖️ Fairness & Subgroup Performance
- Performance breakdown by `SeniorCitizen`, `Gender`, etc.  
- Recall/precision analysis for bias detection

---

## 🏠 Use Case
**Ideal for:**
- Data scientists building end-to-end ML pipelines  
- Analysts presenting churn risk to business stakeholders  
- Students demonstrating predictive modeling in their portfolio

---

## 📄 Project Preview

### 🔹 SHAP Summary Plot

![SHAP Summary](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Assets/churn_shap_summary.png)

### 🔹 Confusion Matrix

![Confusion Matrix](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Assets/churn_conf_matrix.png)

### 🔹 ROC Curve

![ROC Comparison](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Assets/churn_roc_curve.png)

---

### 📥 Download Notebook
[📘 Telco_Customer_Churn.ipynb](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Business_Dashboards/Churn_Prediction/Telco_Customer_Churn.ipynb)

---

## 🎓 Author
**Zaurez Hamid**  
[LinkedIn](https://www.linkedin.com/in/zaurez-h/) | [GitHub](https://github.com/Zaurezzh)

---

## ✈️ Contact & Feedback
Feel free to reach out for feedback, collaboration, or questions!
