# 📊 Stock Market Risk & Return Analysis using Python

## 📌 Project Overview
This project performs a **risk and return analysis** of selected technology stocks using Python and historical market data.  
Instead of focusing on price prediction, the emphasis is on **understanding stock behavior**, including trends, volatility, correlations, and downside risk.

The analysis demonstrates how financial data can be explored, visualized, and interpreted to support informed decision-making — a core skill for data analyst and financial analyst roles.

---

## 🎯 Objectives
The key objectives of this project are:
- Analyze historical stock price movements
- Measure daily return volatility
- Identify trends using moving averages
- Examine correlations between stocks for diversification insights
- Estimate downside risk using **Value at Risk (VaR)**

---

## 📂 Data Source
- **Source:** Yahoo Finance  
- **Access Method:** `yfinance` Python package  
- **Stocks Analyzed:**
  - Apple (AAPL)
  - Amazon (AMZN)
  - Google (GOOGL)
  - Microsoft (MSFT)
- **Time Period:** 2019 – 2024  
- **Frequency:** Daily data

Adjusted closing prices are used to ensure accuracy in return calculations.

---

## 🛠️ Tech Stack
- **Python**
- **yfinance** – Financial data retrieval
- **pandas / numpy** – Data manipulation & numerical analysis
- **matplotlib / seaborn** – Data visualization
- **Monte Carlo Simulation** – Risk estimation (VaR)

---

## 📘 Notebook Structure

### ⚙️ Setup & Imports
Imports all required libraries and defines the stock tickers and analysis time period.

---

### 📥 Fetch Historical Data
Downloads historical **Adjusted Close** prices and trading volumes using the `yfinance` API.

---

### 🔎 Exploratory Data Analysis (EDA)
- Summary statistics (`.info()`, `.describe()`)
- Visualization of closing prices over time
- Trading volume analysis  
This step builds intuition around price trends and market activity.

---

### 📈 Daily Returns
- Calculates day-to-day percentage price changes
- Visualizes return time series
- Displays return distributions to assess volatility and risk

---

### 📊 Moving Averages
- Computes 20-day and 50-day moving averages
- Highlights short-term momentum and long-term trends
- Commonly used in technical market analysis

---

### 🤝 Correlation Analysis
- Scatter plots and pairplots of stock returns
- Correlation heatmap
- Helps identify diversification opportunities and co-movement between stocks

---

### ⚠️ Value at Risk (VaR)
Uses **Monte Carlo simulation** to estimate downside risk:
- Calculates the potential maximum daily loss at a 95% confidence level
- Provides a quantitative risk threshold commonly used in finance

---

### 💡 Insights & Conclusion
- Stocks exhibit varying levels of volatility and risk
- Moving averages reveal clear trend patterns
- Correlation analysis highlights diversification benefits
- VaR quantifies downside exposure in practical terms

**Key Takeaway:**  
This project demonstrates a structured approach to financial risk analysis using real-world data, strong visualization, and clear interpretation — forming a solid foundation for advanced portfolio analysis or predictive modeling.

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook stock_risk_return_analysis.ipynb
