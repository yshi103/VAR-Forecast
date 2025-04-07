# VAR Forecast: Macroeconomic Time Series Modeling

This small project demonstrates the use of a Vector Autoregression (VAR) model to analyze and forecast interrelated macroeconomic time series variables.
The goal is to simulate the forecasting behavior of central banks or financial institutions when faced with multiple interacting economic indicators (e.g., inflation, GDP, interest rates).

## Model

The VAR model captures the linear interdependencies among multiple time series. Key steps include:
- Data preprocessing and visualization
- Stationarity testing (ADF)
- Lag length selection (AIC, BIC)
- Model fitting and diagnostics
- Forecasting and impulse response analysis

## 📈 Results

The model produces multi-step forecasts and interpretable impulse response functions, illustrating how shocks to one variable propagate through the system.

## 🔧 Tools

- Python 3
- statsmodels
- pandas, matplotlib, seaborn
