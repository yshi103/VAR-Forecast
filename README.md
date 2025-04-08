# 📉 Macroeconomic Forecasting with VAR Model

This project applies a Vector Autoregression (VAR) model to analyze the dynamic interactions among key macroeconomic indicators and forecast their future trajectories. The variables include GDP, inflation (CPI), and the federal funds rate. The goal is to understand the transmission of shocks and provide interpretable insights for policy analysis.

## 🔍 Overview

- Data preprocessing and stationarity testing using the Augmented Dickey-Fuller (ADF) test  
- Optimal lag selection based on AIC/BIC  
- Estimation of a multivariate VAR model using `statsmodels`  
- Multi-step forecasting and forecast uncertainty bands  
- Impulse Response Functions (IRFs) to analyze the effects of monetary shocks

## 🧠 Key Insights

- A positive interest rate shock leads to a delayed decline in GDP and inflation  
- Forecasts show widening confidence intervals over longer horizons  
- The model aligns with standard macroeconomic intuition regarding policy transmission lags

## 📁 Files

- `VAR_Forecast.ipynb` — Python notebook containing all code and results  
- `VAR_Forecast_Report.pdf` — Summary write-up with modeling steps, findings, and policy interpretation  
- `README.md` — This file

## 📌 Tools Used

- Python 3  
- pandas, matplotlib, seaborn  
- statsmodels (for VAR estimation)  
- numpy

## ✍️ Contact

**Yuqi Shi**  
Email: yshi103@alumni.jh.edu

