# Stock Price and Volatility Forecasting: Time Series Analysis

## Overview

This project applies advanced time series models to forecast stock prices and estimate market volatility. Using historical stock data, the analysis focuses on capturing both price trends and volatility dynamics using a combination of ARIMA and GARCH models.

## Key Highlights

- 📊 **Exploratory Data Analysis (EDA):**  
  Visualized stock prices and returns to identify trends, seasonality, and volatility clusters.

- 🔍 **Stationarity Testing:**  
  Applied the **Augmented Dickey-Fuller (ADF)** test to assess and transform the time series into a stationary process suitable for modeling.

- 📈 **Modeling Techniques:**  
  - **ARIMA (AutoRegressive Integrated Moving Average)** was used for stock price prediction.  
  - **GARCH (Generalized Autoregressive Conditional Heteroskedasticity)** was used for modeling and forecasting volatility.

- 🔁 **Walk-Forward Validation:**  
  Implemented to evaluate model performance on rolling time windows, ensuring robust and realistic forecasting results.

## Results

- Successfully captured key price and volatility dynamics in the data.
- ARIMA provided reasonable short-term forecasts for stock prices.
- GARCH effectively modeled volatility clustering and variance shifts.

## Tools & Libraries

- Python  
- `pandas`, `numpy`, `matplotlib`, `statsmodels`, `arch`

## Conclusion

The project demonstrates a complete time series forecasting workflow, integrating ARIMA and GARCH models for price and volatility analysis. The approach is suitable for financial time series where capturing both trend and risk is crucial.

## Future Work

- Explore multivariate models like VAR or multivariate GARCH.
- Incorporate exogenous variables (e.g., macroeconomic indicators).
- Extend to portfolio-level volatility modeling.

