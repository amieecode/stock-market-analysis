# stock-market-analysis
## Project Overview

This project focuses on analyzing stock market data and financial statements to gain insights into company performance. Using Python and financial data from Yahoo Finance, the analysis combines **technical (price-based)** and **fundamental (financial statement)** approaches.

The primary focus is on:

* Apple Inc. (AAPL)
* Tesla, Inc. (TSLA)

---

## bjectives

* Fetch historical stock data using `yfinance`
* Analyze stock price trends and performance
* Resample time-series data for different intervals
* Visualize stock movements using `matplotlib`
* Extract and analyze financial statements:

  * Income Statement
  * Balance Sheet
  * Cash Flow Statement
* Evaluate company performance using key financial metrics

---

## Tools & Technologies
* Python
* Pandas
* Matplotlib
* YFinance

---

## Data Collection

Stock market and financial data were obtained using the `yfinance` library, which provides:

* Adjusted closing prices
* Historical stock data (multiple intervals)
* Financial statements (income, balance sheet, cash flow)
* No API key required

---

## Data Cleaning

* Removed fully empty rows using `dropna(how='all')`
* Handled missing values using forward-fill (`ffill`)
* Sorted data for proper time-series analysis
* Converted values into billions for readability

> Financial datasets often contain missing values due to differences in reporting periods. Instead of removing all missing data, appropriate techniques were applied to preserve meaningful insights.

---

## Stock Price Analysis

* Visualized adjusted closing prices
* Compared stock performance between Apple and Tesla
* Identified trends and volatility patterns
* Applied different time intervals (daily, hourly, etc.)

---

## Time-Series Resampling

* Converted high-frequency data (1-minute) into custom intervals (e.g., 10-minute, hourly)
* Enabled flexible analysis for trading strategies and trend observation

---

## Financial Statement Analysis

### Income Statement

* Total Revenue
* EBIT (Operating Income)
* Net Income

### Balance Sheet

* Total Assets
* Total Debt
* Cash & Cash Equivalents
* Shareholder Equity

### Cash Flow Statement

* Operating Cash Flow
* Free Cash Flow

---

## Key Insights

### Apple Inc.

* Strong and consistent revenue growth
* Increasing EBIT indicates operational efficiency
* High liquidity with strong cash reserves
* Declining debt levels show improved financial stability

### Tesla, Inc.

* Higher stock price volatility
* Growth-driven financial structure
* More aggressive expansion strategy compared to Apple

---

## Data Visualization

* Bar charts for financial metrics
* Line plots for stock prices
* Gridlines, labels, and proper scaling for readability

---

## Why This Project Stands Out

* Combines **technical + fundamental analysis**
* Handles real-world messy financial data
* Demonstrates data cleaning and transformation skills
* Provides business-level insights, not just code output

---

## Key Learnings

* Working with real-world financial datasets
* Handling missing values effectively
* Time-series data manipulation and resampling
* Financial statement interpretation
* Building end-to-end data analysis projects

---

## Future Improvements

* Add financial ratios (ROE, Debt-to-Equity, Profit Margins)
* Build an interactive dashboard (Power BI / Streamlit)
* Include predictive modeling for stock prices
* Expand analysis to more companies

---

## If you found this useful

Feel free to star the repository and connect with me!

