
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

You can install the required libraries using the following commands:

```bash
pip install pandas numpy matplotlib seaborn plotly yfinance
```

Alternatively, you can use `conda` to install the required packages:

```bash
conda install pandas numpy matplotlib seaborn plotly
conda install -c conda-forge yfinance
```

---

## Installation and Setup

1. Clone or download this repository.
   
   ```bash
   git clone https://github.com/your-username/financial-ratio-analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd financial-ratio-analysis
   ```

3. Install the necessary libraries (if not already done):

   ```bash
   pip install -r requirements.txt
   ```

---

## How to Use

1. Open the `financial_analysis.ipynb` Jupyter notebook.
2. Run the cells in sequence to:
   - Download stock data.
   - Calculate the P/E and ROE ratios.
   - Visualize the data using interactive plots.
   - Generate insights based on the financial metrics.

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

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **Yahoo Finance API:** Data sourced from Yahoo Finance using `yfinance`.
- **Matplotlib, Seaborn, Plotly:** Used for data visualization.

---

## Future Enhancements

- Add more financial ratios like Debt-to-Equity, Dividend Yield, etc.
- Implement time series forecasting models to predict stock prices.
- Perform a deeper analysis of sector-specific trends.
