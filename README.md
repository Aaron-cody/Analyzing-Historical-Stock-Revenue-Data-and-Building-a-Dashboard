# Historical Stock and Revenue Dashboard Analysis

## Short Overview

A Python-based financial dashboard comparing Tesla and GameStop using stock prices, revenue data, return metrics, volatility, drawdowns, and interactive Plotly visualizations.

This repository began as an IBM/course-style educational project for extracting and visualizing stock and revenue data. It now includes an upgraded finance dashboard notebook that expands the analysis while keeping the project honest, readable, and focused.

## Live Dashboard

The interactive Plotly dashboard is available through GitHub Pages:

[Open the live financial dashboard](https://aaron-cody.github.io/Analyzing-Historical-Stock-Revenue-Data-and-Building-a-Dashboard/financial_dashboard.html)

Note: GitHub may not preview the large HTML file directly inside the repository, so GitHub Pages is used to view the interactive dashboard.

## Objective

The objective of this project is to practice a practical finance data workflow:

- Collect historical stock price data with Python.
- Scrape company revenue tables from web pages.
- Clean and prepare financial datasets for analysis.
- Calculate return and risk metrics.
- Build interactive dashboard-style visualizations with Plotly.
- Interpret stock price behavior alongside revenue trends.

## Tools and Libraries Used

- Python
- Jupyter Notebook
- pandas
- numpy
- yfinance
- requests
- BeautifulSoup
- Plotly
- plotly.subplots

## Data Sources

- Historical stock price data from Yahoo Finance through the `yfinance` Python library.
- Tesla and GameStop revenue data from IBM course-hosted HTML pages based on Macrotrends-style revenue tables.

## Key Tasks Performed

- Extracted Tesla and GameStop historical stock data using `yfinance`.
- Scraped quarterly revenue data with `requests` and `BeautifulSoup`.
- Cleaned date, price, return, and revenue fields.
- Calculated daily returns, cumulative returns, annualized return, annualized volatility, maximum drawdown, Sharpe ratio, latest closing price, and total return.
- Created interactive Plotly charts comparing price, returns, volatility, drawdowns, and revenue.
- Built a KPI summary table comparing Tesla and GameStop.

## Main Outputs

- [financial_dashboard_analysis.ipynb](financial_dashboard_analysis.ipynb): Upgraded finance dashboard analysis with return metrics, risk metrics, drawdowns, revenue comparison, KPI summary, and interactive Plotly visualizations.
- `financial_dashboard.html`: HTML export of the main interactive Plotly dashboard, published through GitHub Pages.

## Extended Analysis

The dashboard notebook adds a finance-oriented layer to the original project:

- Tesla vs GameStop normalized price chart.
- Tesla vs GameStop cumulative return chart.
- Rolling 30-day annualized volatility chart.
- Drawdown chart showing peak-to-trough declines.
- Revenue comparison chart.
- Dashboard-style subplot combining price, cumulative return, volatility, drawdown, revenue, and KPI metrics.
- Professional interpretation of Tesla as a growth-stock example and GameStop as a speculative meme-stock episode where market price temporarily disconnected from revenue trends.

## How to Run the Project

1. Clone this repository.
2. Open the notebook in Jupyter Notebook, JupyterLab, VS Code, or another notebook environment.
3. Install the required Python libraries if they are not already available:

   ```bash
   pip install pandas numpy yfinance requests beautifulsoup4 plotly nbformat
   ```

4. Run the notebook:

   ```text
   financial_dashboard_analysis.ipynb
   ```

## Limitations

- This is an educational project, not an investment analysis tool or financial recommendation.
- The notebooks depend on live external data sources, so results may change or fail if websites, APIs, or table structures are updated.
- Revenue data is scraped from static course-hosted pages and may not reflect the latest company filings.
- The analysis is limited to Tesla and GameStop.
- The Sharpe ratio uses a 0% risk-free rate for simplicity.
- The project does not include machine learning, forecasting, econometrics, or valuation modeling.

## What I Learned

- How to retrieve historical market data with `yfinance`.
- How to scrape and parse HTML tables with `requests` and `BeautifulSoup`.
- How to clean financial text data for analysis.
- How to calculate common return and risk metrics in Python.
- How to compare stock price behavior with revenue trends.
- How to present an educational data analysis project in a cleaner, recruiter-friendly GitHub format.

## Suggested GitHub Repository Description

Python project analyzing historical stock prices and company revenue data, with dashboard visualizations using Plotly.

## Suggested GitHub Topics

`python` `finance` `data-analysis` `stock-market` `web-scraping` `yfinance` `plotly` `dashboard`
