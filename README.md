# 📊 Unemployment Rate Forecasting – CodeAlpha Internship

This project is completed as part of my internship with **CodeAlpha**.

## 🔖 Task Name: `Unemployment_Rate_Forecasting`
- **Dataset**: [Kaggle - Unemployment in India](https://www.kaggle.com/datasets/rajanand/unemployment-in-india)
- **Domain**: Data Science / Time Series Forecasting

---

## 📁 Dataset Description

The dataset contains monthly unemployment statistics in India, broken down by state and area (Rural/Urban), from May 2019 to June 2020. It includes:
- `Estimated Unemployment Rate (%)`
- `Estimated Employed`
- `Estimated Labour Participation Rate (%)`

---

## 🔧 Project Workflow

### 1. 📥 Data Loading & Cleaning
- Loaded `.csv` from Google Drive
- Renamed columns, converted `Date` to datetime
- Cleaned numeric fields and extracted Year, Month, and State

### 2. 📊 Exploratory Data Analysis (EDA)
- Visualized unemployment rate distribution and time trends
- Correlation matrix to identify feature relationships
- Compared Rural vs Urban and Pre-COVID vs Post-COVID trends
- Identified top 10 states with highest unemployment

### 3. 🔍 Time Series Decomposition
- National unemployment trend was decomposed into trend, seasonality, and residuals using `seasonal_decompose`.

### 4. 🤖 Forecasting with ARIMA
- Trained ARIMA(1,1,1) on national average unemployment rate
- Forecasted next 3 months
---

## 📈 Results & Key Insights

- **COVID-19** caused a sharp increase in unemployment from April 2020
- **Rural** and **Urban** areas showed different recovery patterns
- **Forecasted U-rates** for the next 3 months were visualized and validated

---

## 🧰 Libraries Used
```bash
- pandas, numpy
- matplotlib, seaborn
- statsmodels (ARIMA, decomposition)
- scikit-learn (metrics)
- plotly (optional interactive plots)
```

➡️ [GitHub Repo](https://github.com/Abre1234/CodeAlpha_Sales_Prediction)
