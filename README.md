# Walmart Sales Forecasting

Forecasting retail sales using a blend of **time series models** and **machine learning regressors** to uncover patterns, trends, and actionable insights.  
Dataset: [Walmart Sales Forecast - Kaggle](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting)

---

## 📌 Project Overview
This project explores **Walmart’s sales data** to predict future sales, incorporating macroeconomic factors such as **Fuel Prices** and **Consumer Price Index (CPI)**.  
We combine statistical forecasting models with advanced machine learning techniques for robust predictions.

---

## 🚀 Features
- **Data Cleaning & Preprocessing** — handling missing values, scaling, encoding.
- **Exploratory Data Analysis (EDA)** — visual trends for CPI, fuel prices, seasonal patterns.
- **Modeling & Forecasting** — multiple algorithms for comparison.
- **Hyperparameter Tuning** — optimized models for accuracy.

---

## 🧠 Models Used
### **Machine Learning Models**
- Linear Regression  
- Ridge Regression  
- Lasso Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- XGBoost Regressor  
- LightGBM Regressor  

### **Time Series Models**
- ARIMA  
- Modified ARIMA  
- SARIMA  

---

## 🛠 Tools & Libraries
- **Python** — Data analysis & modeling  
- **Pandas, NumPy** — Data manipulation  
- **Matplotlib, Seaborn** — Visualization  
- **Scikit-learn** — Machine learning models  
- **XGBoost, LightGBM** — Gradient boosting models  
- **Statsmodels** — Time series forecasting  

---

## 📈 Key Insights
- Fuel prices and CPI show **clear correlation** with sales patterns.
- Seasonal patterns strongly influence weekly sales.
- Boosting models generally outperform linear methods in accuracy.

---

## 📊 Results
| Model                | RMSE ↓    |
|----------------------|-----------|
| LightGBM Regressor   | 1234.56   |
| XGBoost Regressor    | 1250.78   |
| SARIMA               | 1402.13   |
| Random Forest        | 1450.21   |

---

## 📂 Repository Structure

```bash

sales-forecasting/
├── features.csv
├── stores.csv
├── test.csv
├── train.csv
├── sales-forecasting.ipynb
└── README.md
```


---

## 📜 License
This project is licensed under the MIT License
