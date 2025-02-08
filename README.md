
# Financial Ratios Analysis for Publicly Listed Companies

## Overview

This project demonstrates how to analyze key financial ratios such as Price-to-Earnings (P/E) ratio and Return on Equity (ROE) for publicly listed companies. By leveraging stock data from Yahoo Finance, the analysis provides insights into company performance, stock price trends, and key financial metrics.

### Objective
The goal of this project is to:
- Retrieve stock price data for major companies.
- Calculate key financial ratios, such as P/E and ROE, using the companies' financial statements.
- Visualize stock price trends and compare financial ratios across companies.
- Generate actionable insights from the data.

### Key Features
- **Data Collection:** Use the Yahoo Finance API to download historical stock data.
- **Financial Ratios Calculation:** Calculate important ratios like P/E and ROE.
- **Visualization:** Create interactive and informative visualizations to represent trends and comparisons.
- **Analysis:** Provide insights based on calculated financial ratios.

---

## Requirements

Before running the Jupyter notebook, ensure you have the following libraries installed:

- **Python 3.x**
- **Libraries:**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `plotly`
  - `yfinance`

---


## Data Sources

- **Yahoo Finance:** Stock data is retrieved using the `yfinance` library, which accesses historical price data for various companies.
- **Financial Statements:** Mock financial data for calculating P/E and ROE ratios is included. This data can be replaced with real-world financial statements for more accurate calculations.

---

## Visualizations

This project generates the following visualizations:

- **P/E Ratio:** A bar chart comparing the P/E ratios of selected companies.
- **ROE:** A bar chart displaying the Return on Equity (ROE) for each company.
- **Stock Price Trends:** A line plot showing the stock price movements over time for the selected companies.

---

## Insights

The financial ratios are analyzed to offer the following insights:

- **P/E Ratio:** If a company's P/E ratio is high, it may indicate overvaluation; if low, it may suggest undervaluation.
- **ROE:** A high ROE suggests strong profitability, while a low ROE may signal inefficiencies.

---

## Acknowledgments

- **Yahoo Finance API:** Data sourced from Yahoo Finance using `yfinance`.
- **Matplotlib, Seaborn, Plotly:** Used for data visualization.


