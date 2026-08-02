# 📈 Stock Price Time Series Analysis & Predictive Modeling (Apple Inc. - AAPL)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-Time%20Series-orange)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Environment-F9AB00?logo=googlecolab&logoColor=white)

An end-to-end time series analysis and forecasting project examining historical stock market data for **Apple Inc. (AAPL)** from 2023 to 2026. This project extracts market trends, breaks down seasonality components, measures risk via rolling volatility, maps trading day distributions, and projects future prices using an **ARIMA** model.

---

## 🚀 Project Overview

Financial time series data are inherently non-stationary and prone to high volatility clustering. This repository implements a rigorous analytical workflow in **Google Colab** using Python to dissect price movements, smooth out noise, and generate statistical insights.

### Key Objectives:
* **Trend Analysis:** Smoothing high-frequency noise using Moving Averages (50-Day and 200-Day SMA).
* **Seasonality & Decomposition:** Isolating trend, seasonal, and residual components.
* **Risk & Volatility Analysis:** Calculating daily percentage returns, return distributions, and annualized 30-day rolling volatility.
* **Predictive Forecasting:** Building and projecting future prices via an AutoRegressive Integrated Moving Average (ARIMA) model.
* **Statistical Summary:** Tabulating performance metrics, including total return, maximum daily gain/loss, and trade proportions.

---

## 🛠️ Tech Stack & Libraries

* **Data Retrieval & Manipulation:** `yfinance`, `pandas`, `numpy`
* **Statistical Modeling:** `statsmodels` (ARIMA, Seasonal Decomposition)
* **Data Visualization:** `matplotlib`, `seaborn`
* **Development Environment:** `Google Colab` (`.ipynb`)

---

## 📊 Analytical Pipeline & Visualizations

1. **Moving Average Crossovers:** Evaluates medium-term vs. long-term market momentum.
2. **Time Series Decomposition:** Additive breakdown of trend, weekly/yearly periodicity, and noise residuals.
3. **Daily Returns & KDE Distribution:** Explores return skewness and kurtosis.
4. **Annualized Rolling Volatility:** Highlights periods of high market turbulence with gradient fill styling.
5. **Trading Days Pie Chart:** Classifies proportion of positive, negative, and flat trading sessions.
6. **ARIMA Price Forecasting:** Projects a 30-day forward trend based on historical autoregression.

---

## 📈 Summary Performance Metrics

| Metric | Value |
| :--- | :--- |
| **Starting Price (Jan 2023)** | $122.98 |
| **Ending Price (Dec 2025)** | $271.36 |
| **Total Return** | +120.65% |
| **Annualized Volatility** | 23.81% |
| **Max Daily Gain** | +15.33% |
| **Max Daily Loss** | -9.25% |

---

## 📂 Repository Structure

```text
├── stock-market-analysis-prediction-using-lstm.ipynb  # Core LSTM & Time Series Notebook
├── Task7nayan.ipynb                                   # Primary Analysis & Visualization Script
└── README.md                                          # Project Documentation
