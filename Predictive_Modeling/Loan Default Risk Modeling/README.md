
# 💰 Loan Default Risk Modeling (Python)

This machine learning project predicts loan approval status using classification models on a real-world financial dataset. It combines advanced EDA, feature engineering, and model interpretability to support credit decision-making and demonstrate end-to-end predictive analytics.





---

## 🌐 Project Overview
- **Tool**: Python (Google Colab)
- **Dataset**: [Loan Prediction Dataset – Kaggle](https://www.kaggle.com/datasets/ninzaami/loan-predication)
- **File Used**: `train_u6lujuX_CVtuZ9i.csv`
- **Objective**: Build a classification model to predict loan approval based on applicant data such as income, credit history, education, and marital status.

---

## 📊 Key Features

### ✅ Data Exploration & Feature Engineering
- Missing value analysis via heatmaps  
- Distribution plots for numeric features (skewed data detection)  
- Bivariate analysis with stacked bar charts:  
  - `Loan_Status` vs `Credit_History`, `Education`, `Marital_Status`  
- Engineered features: `Total_Income`, `EMI`, `Balance_Income`


### 🧼 Preprocessing
- Missing value imputation using mode and median
- Label encoding for categorical variables
- Outlier and skewness detection

### 🔍 Modeling
- **Logistic Regression**: Interpretable linear model for baseline  
- **Decision Tree Classifier**: Captures non-linear relationships  
- Train/Test split with 70:30 ratio  
- **Evaluation Metrics**:  
  - Confusion matrix  
  - Precision, Recall, F1-score  
  - ROC-AUC score  


### 📈 Interpretability & Performance
- ROC curve with AUC comparison for models  
- Feature importance chart (Decision Tree)  
- Ranked list of top predictive features


---

## 🧠 Skills Demonstrated
- Exploratory Data Analysis (EDA)  
- Feature Engineering & Transformation  
- Classification Modeling (Logistic Regression, Decision Tree)  
- ROC-AUC and Confusion Matrix Interpretation  
- Model Evaluation & Feature Importance  


## 🧩 Visual Outputs

| Confusion Matrix | ROC Curve | Feature Importance |
|------------------|-----------|---------------------|
| ![Confusion Matrix](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Assets/Loan_Confusion%20Matrix.PNG) | ![ROC Curve](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Assets/Loan_ROC.PNG) | ![Feature Importance](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Assets/Loan_Feature%20Importance.PNG) |

---

## 🏠 Use Case
**Ideal for:**
- Credit risk modeling in banking and finance  
- Data science learners practicing classification pipelines  

---

## 📄 Notebook Preview
[📥 loan_default_model.ipynb](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Predictive_Modeling/Loan%20Default%20Risk%20Modeling/Loan_default.ipynb)

---

## 🎓 Author
**Zaurez Hamid**  
[LinkedIn](https://www.linkedin.com/in/zaurez-h/) | [GitHub](https://github.com/Zaurezzh)

