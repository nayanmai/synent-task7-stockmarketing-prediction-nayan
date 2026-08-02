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
# 📈 Visualizations & Analytical Breakdown

Below are the key analytical charts and visual models generated during the time series analysis of Apple Inc. (AAPL) stock data:



### 1. Stock Price Trend Analysis & Moving Averages
Image Name / File Concept: Moving Averages Trend / stock_trend_ma.png

Visual Representation: (Screenshot 2026-08-02 234743.png)

Description: This chart plots the daily closing stock price (light blue line) alongside a 50-Day Simple Moving Average (orange line) and a 200-Day Simple Moving Average (red line) over a multi-year period (2023–2026). It smooths out high-frequency market noise to help identify major structural momentum shifts, trend reversals, and support/resistance crossings.

## 2. Time Series Decomposition
Image Name / File Concept: Decomposition / time_series_decomposition.png

Visual Representation: (Screenshot 2026-08-02 234752.png & 234845.png)

Description: This multi-panel analytical graph breaks down the historical stock pricing data into its fundamental components:

Observed: The raw historical stock price series.

Trend: The underlying long-term progression free of seasonal and random fluctuations.

Seasonal: The repeating cyclical patterns or regular periodic variations over time.

Residual (Resid): The irregular, random noise or leftover variance remaining after removing trend and seasonality.


## 3. Daily Returns & Return Distribution
Image Name / File Concept: Returns Distribution / daily_returns_distribution.png

Visual Representation: (Screenshot 2026-08-02 234917.png)

Description: Presented in a dual-panel layout:

Daily Percentage Returns (Left): Tracks day-over-day percentage changes, highlighting volatility spikes, market shocks, and outlier gain/loss days (such as the sharp drop/spike near early 2025).

Distribution of Daily Returns (Right): Combines a frequency histogram with a Kernel Density Estimation (KDE) curve (yellow line) to inspect market skewness, kurtosis, and the concentration of typical daily price shifts around zero.
## 4. Rolling Volatility Analysis (Annualized)
Image Name / File Concept: Rolling Volatility / rolling_volatility.png

Visual Representation: (Screenshot 2026-08-02 234929.png & 234923.png)

Description: Evaluates market turbulence dynamically by calculating a 30-day sliding window of annualized standard deviation on returns. The line graph highlights calm accumulation phases alongside sharp volatility spikes (notably soaring near mid-2025), illustrating periods of heightened risk and market uncertainty.

## 5. ARIMA Price Forecasting
Image Name / File Concept: ARIMA Forecast / arima_forecast.png

Visual Representation: (Screenshot 2026-08-02 234854.png & 234800.png)

Description: Projects a future trajectory using autoregressive modeling. It contrasts historical closing prices (solid blue line) against a 30-business-day forward prediction path (dashed or solid green line), modeling short-term expectations based on historical lag patterns and moving average parameters.
---

## 📂 Repository Structure

```text
├── assets/                                            # Directory for output graphs & visual exports
├── stock-market-analysis-prediction-using-lstm.ipynb  # Core LSTM & Time Series Notebook
├── Task7nayan.ipynb                                   # Primary Analysis & Visualization Script
└── README.md                                          # Project Documentation
