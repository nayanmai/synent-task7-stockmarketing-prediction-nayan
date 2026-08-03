# 📈 Stock Price Time Series Analysis & Predictive Modeling (Apple Inc. - AAPL)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-Time%20Series-orange)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Environment-F9AB00?logo=googlecolab&logoColor=white)

An end-to-end **Time Series Analysis and Forecasting** project that analyzes historical stock prices of **Apple Inc. (AAPL)** using statistical techniques and predictive modeling. The project identifies market trends, decomposes seasonal components, measures market volatility, visualizes trading behavior, and forecasts future stock prices using the **ARIMA** model.

---

# 👩‍💻 Project Header

**Student Name:** Nayan Maity

**Level:** Advanced Level (Task 7)

**Tools Used:**
- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- yfinance
- Google Colab

**Project Output**
- Trend Analysis
- Moving Average Analysis
- Seasonality Decomposition
- Volatility Analysis
- Daily Return Analysis
- ARIMA Forecasting
- Financial Performance Metrics

---

# 🎯 Problem Statement

Financial markets generate large volumes of sequential data that continuously change over time. Traditional analytical techniques cannot effectively capture hidden temporal patterns, long-term trends, seasonality, or market volatility.

The objective of this project is to perform comprehensive time series analysis on Apple Inc. (AAPL) historical stock prices to:

- Analyze long-term market trends.
- Detect seasonal behavior.
- Measure stock volatility.
- Forecast future stock prices.
- Generate meaningful visual insights for financial decision-making.

---

# 📊 Dataset Details

**Dataset Source:** Kaggle

**Dataset Name:** Apple Stock Price Dataset (AAPL)

**Platform:** Kaggle

**Time Period:**
- Start Date: January 2023
- End Date: January 2026

### Features Used

- Date
- Open
- High
- Low
- Close
- Adjusted Close
- Volume

The analysis primarily focuses on the **Closing Price** to perform trend analysis, volatility analysis, seasonality decomposition, and stock price forecasting using the ARIMA model.
---

# ⚙️ Project Approach

The project follows the complete Time Series Analysis workflow.

### 1️⃣ Data Collection

- Downloaded historical stock prices using the Yahoo Finance API (`yfinance`).
- Imported the dataset into Google Colab for analysis.

---

### 2️⃣ Data Preprocessing

- Cleaned missing values.
- Selected daily closing prices.
- Converted data into a proper time-series format.

---

### 3️⃣ Trend Analysis

Calculated:

- 50-Day Moving Average
- 200-Day Moving Average

These indicators smooth short-term fluctuations and reveal long-term market trends.

---

### 4️⃣ Seasonality Detection

Applied **Seasonal Decomposition** to separate the stock prices into:

- Trend
- Seasonal Component
- Residual Component

---

### 5️⃣ Forecasting

Implemented the **ARIMA (5,1,0)** model to forecast the next **30 business days** of Apple stock prices.

---

### 6️⃣ Volatility Analysis

Calculated:

- Daily Percentage Returns
- 30-Day Rolling Annualized Volatility

This helps measure market risk and identify highly volatile trading periods.

---

### 7️⃣ Performance Summary

Generated important financial metrics such as:

- Total Return
- Annualized Volatility
- Maximum Daily Gain
- Maximum Daily Loss

---

# 📊 Summary Performance Metrics

| Metric | Value |
|---------|--------|
| Starting Price (Jan 2023) | $122.98 |
| Ending Price (Dec 2025) | $271.36 |
| Total Return | **+120.65%** |
| Annualized Volatility | **23.81%** |
| Max Daily Gain | **+15.33%** |
| Max Daily Loss | **−9.25%** |

---

# 📈 Results

The analysis generated several meaningful financial insights:

- Successfully identified long-term stock price trends using Moving Averages.
- Decomposed the time series into Trend, Seasonal, and Residual components.
- Forecasted future stock prices using the ARIMA model.
- Measured market volatility using rolling annualized volatility.
- Visualized daily returns and return distributions.
- Summarized key financial performance indicators for investment analysis.

---

# 📈 Visualizations & Analytical Breakdown

The project contains multiple analytical charts that explain different aspects of Apple's historical stock performance.

---

## 1️⃣ Stock Price Trend Analysis & Moving Averages

**Image:** `assets/stock_trend_ma.png`

**Description**

Displays the daily closing price together with the **50-Day** and **200-Day Moving Averages**, helping identify long-term market trends, trend reversals, and momentum changes.

---

## 2️⃣ Time Series Decomposition

**Image:** `assets/time_series_decomposition.png`

**Description**

Breaks the stock price into four components:

- Observed
- Trend
- Seasonal
- Residual

This helps understand the underlying structure of the time series.

---

## 3️⃣ Daily Returns & Return Distribution

**Image:** `assets/daily_returns_distribution.png`

**Description**

Shows:

- Daily percentage returns
- Histogram of returns
- Kernel Density Estimation (KDE)

Useful for analyzing return distribution, volatility, and market behavior.

---

## 4️⃣ Rolling Volatility Analysis

**Image:** `assets/rolling_volatility.png`

**Description**

Calculates the **30-Day Annualized Rolling Volatility** to identify periods of high and low market risk.

---

## 5️⃣ ARIMA Price Forecasting

**Image:** `assets/arima_forecast.png`

**Description**

Forecasts Apple's stock price for the next **30 business days** using an ARIMA model and compares historical prices with predicted values.

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- yfinance
- Google Colab

---

# 📂 Repository Structure

```text
📦 Stock-Price-Time-Series-Analysis
│
├── assets/
│   ├── stock_trend_ma.png
│   ├── time_series_decomposition.png
│   ├── daily_returns_distribution.png
│   ├── rolling_volatility.png
│   ├── arima_forecast.png
│   └── summary_metrics.png
│
├── stock-market-analysis-prediction-using-lstm.ipynb
├── Task7nayan.ipynb
├── requirements.txt
└── README.md
```

---

# 🎯 Key Learning Outcomes

- Time Series Analysis
- Financial Data Analytics
- Moving Average Analysis
- Seasonal Decomposition
- ARIMA Forecasting
- Stock Market Trend Analysis
- Volatility Measurement
- Data Visualization
- Predictive Analytics
- Python for Financial Modeling

---

# 🔮 Future Enhancements

- Implement LSTM Deep Learning models for forecasting.
- Compare ARIMA with Facebook Prophet and XGBoost.
- Perform Hyperparameter tuning using Auto-ARIMA.
- Develop an interactive dashboard using Streamlit or Power BI.
- Extend the analysis to multiple stocks for comparative insights.

---

# 📌 Conclusion

This project demonstrates how **Time Series Analysis** can transform historical stock market data into actionable financial insights. By combining trend analysis, seasonal decomposition, volatility measurement, and ARIMA forecasting, the project provides a structured framework for understanding stock price behavior and supporting informed investment decisions. It also strengthened practical skills in **Python, Financial Analytics, Statistical Modeling, and Data Visualization**.

---

# 👨‍💻 Author

**Nayan Maity**

Aspiring Data Analyst | Python Developer | Machine Learning Enthusiast

📧 Email: *maity2nayan@gmail.com*

🔗 LinkedIn: *linkedin.com/in/nayan-maity-it-workers*

---

⭐ **If you found this project useful, consider giving it a Star!**
