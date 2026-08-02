# 📈 Stock Price Time Series Analysis & Predictive Modeling (Apple Inc. - AAPL)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-Time%20Series-orange)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Environment-F9AB00?logo=googlecolab&logoColor=white)

An end-to-end time series analysis and forecasting project examining historical stock market data for **Apple Inc. (AAPL)** from 2023 to 2026. This project extracts market trends, breaks down seasonality components, measures risk via rolling volatility, maps trading day distributions, and projects future prices using an **ARIMA** model.

---

## 👩‍💻 Project Header

* **Student Name:** Nandita Manna  
* **Level:** Advanced Level (Task 7)  
* **Tools Used:** Python (pandas, numpy, matplotlib, statsmodels, yfinance), Google Colab  
* **Output:** Time-based Trends, Seasonality Decomposition, Volatility Analysis, & Predictive Forecasts  

---

## 📊 Summary Performance Metrics

| Metric | Value |
| :--- | :--- |
| **Starting Price (Jan 2023)** | $122.98 |
| **Ending Price (Dec 2025)** | $271.36 |
| **Total Return** | +120.65% |
| **Annualized Volatility** | 23.81% |
| **Max Daily Gain** | +15.33% |
| **Max Daily Loss** | -9.25% |

---

## 📉 Visualizations & Analytical Breakdown

### 1. Stock Price Trend Analysis & Moving Averages
Smooths high-frequency noise using 50-day and 200-day Simple Moving Averages to track structural momentum shifts.
<!-- Replace path with your actual image path after uploading to GitHub -->
![Moving Averages Trend](assets/trend_ma.png)

### 2. Time Series Decomposition
Deconstructs the historical stock prices into core components: Trend, Seasonality, and Residual noise.
<!-- Replace path with your actual image path -->
![Decomposition](assets/decomposition.png)

### 3. Daily Returns & Return Distribution
Analyzes day-over-day percentage changes alongside Kernel Density Estimation (KDE) to inspect market skewness.
<!-- Replace path with your actual image path -->
![Returns Distribution](assets/returns_dist.png)

### 4. Rolling Volatility Analysis (Annualized)
Tracks market turbulence dynamically over a 30-day sliding window.
<!-- Replace path with your actual image path -->
![Rolling Volatility](assets/volatility.png)

### 5. ARIMA Price Forecasting
Projects a 30-business-day forward prediction path based on historical autoregressive patterns.
<!-- Replace path with your actual image path -->
![ARIMA Forecast](assets/arima_forecast.png)

---

## 📂 Repository Structure

```text
├── assets/                                            # Directory for output graphs & visual exports
├── stock-market-analysis-prediction-using-lstm.ipynb  # Core LSTM & Time Series Notebook
├── Task7nayan.ipynb                                   # Primary Analysis & Visualization Script
└── README.md                                          # Project Documentation
