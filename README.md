# 📈 Stock Price Prediction using Machine Learning

<img width="1033" height="403" alt="project phases diagram" src="https://github.com/user-attachments/assets/a1c0e3c3-db20-43dd-9f14-fa874d5ffdbb" />

## 📌 Overview
This project focuses on forecasting and analyzing stock prices using machine learning models such as Random Forest, XGBoost, and Prophet. The goal is to predict future stock trends based on historical data and provide insights for better financial decision-making.

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Jupyter Notebook

---

## 📊 Features
- Data preprocessing and cleaning  
- Feature engineering  
- Model training and evaluation  
- Visualization of stock trends  
- Comparison of different machine learning models  

---

## 🤖 Models Used
- Random Forest  
- XGBoost  
- Prophet  

---

## 📈 Results

The **XGBoost model** achieved strong predictive performance on stock price forecasting:

| Metric | Train | Validation |
|--------|------|------------|
| RMSE   | 0.224 | 0.398 |
| MAE    | 0.159 | 0.273 |
| MAPE   | 0.995% | 0.872% |
| R² Score | 0.999 | 0.996 |

### 📊 Key Insights
- Achieved **< 1% prediction error (MAPE)**, indicating high accuracy.
- Minimal difference between training and validation results → **low overfitting**.
- XGBoost outperformed **Random Forest and Prophet**, achieving the lowest error and best generalization.
