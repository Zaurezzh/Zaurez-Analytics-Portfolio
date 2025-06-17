# 📈 Sales Forecasting with Machine Learning (Python)

This advanced time series project predicts daily sales for an e-commerce business using multiple forecasting techniques. It includes baseline regression, interpretable Prophet models, and LSTM deep learning — offering a robust comparison of forecasting accuracy and temporal modeling power.

---

## 🌐 Project Overview
- **Tool**: Python (Google Colab)
- **Dataset**: [E-Commerce Dataset – Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)
- **File Used**: `data.csv`
- **Objective**: Forecast daily sales based on historical transactions using multiple models and evaluate performance through RMSE/MAE across short and long horizons.

---

## 📊 Key Features

### ✅ Data Preparation & EDA
- Cleaned and transformed raw invoice-level data into a continuous daily time series
- STL decomposition to separate trend, seasonality, and noise
- Rolling mean visualization, ACF/PACF analysis, and anomaly detection

### 🧼 Preprocessing
- Outlier filtering using STL residual thresholds
- Train/test split using time-based 80/20 methodology
- Feature engineering: lag variables for supervised learning models

### 🔍 Forecasting Models
- **Linear Regression (Baseline)**: Lag-based supervised learning
- **Prophet Model**: Tuned with changepoint & monthly seasonality
- **LSTM (Keras)**: Deep learning sequence model for volatility-sensitive predictions
- **Cross-Validation**: Prophet rolling-window backtesting using `performance_metrics`

---

## 📈 Model Comparison Output

| Prophet CV RMSE | Forecast Plot (Prophet vs Linear vs LSTM) |
|------------------|--------------------------------------------|
| ![Prophet CV RMSE](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Assets/prophet_cv_rmse.png) | ![Forecast Plot](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Assets/sales_forecast_comparison.png) |

---

## 💡 Skills Demonstrated
- Time series forecasting with classical (Prophet) and deep learning (LSTM) models
- STL decomposition, autocorrelation analysis, and anomaly detection
- Feature engineering with lag-based regression
- Hyperparameter tuning and cross-validation using rolling-origin methods
- Model evaluation using RMSE, MAE, and visual comparisons
- Matplotlib/seaborn-based data visualization
- TensorFlow/Keras sequence modeling

---

## 🏠 Use Case
**Ideal for:**
- Inventory and demand planning in e-commerce
- Business forecasting projects across retail and logistics
- Academic showcase (Master’s or PhD-level) for time series modeling expertise

---

## 📄 Notebook Preview
[📥 sales_forecasting.ipynb](https://github.com/Zaurezzh/Zaurez-Analytics-Portfolio/blob/main/Predictive_Modeling/Sales_Forecasting/sales_forecasting.ipynb)

---

## 🎓 Author
**Zaurez Hamid**  
[LinkedIn](https://www.linkedin.com/in/zaurez-h/) | [GitHub](https://github.com/Zaurezzh)

---

## ✉️ Contact & Feedback
Open to feedback, discussions, or collaborations — feel free to reach out!
