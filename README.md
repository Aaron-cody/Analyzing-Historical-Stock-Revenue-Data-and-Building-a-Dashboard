# Historical Stock and Revenue Dashboard Analysis

## Short Overview

This repository contains an educational finance data analysis notebook completed as part of an IBM/course-style Python project. The project extracts historical stock price data and company revenue data, then visualizes both datasets together in interactive Plotly dashboards.

The analysis focuses on Tesla (`TSLA`) and GameStop (`GME`) to compare historical share prices with reported revenue trends.

## Objective

The objective of this project is to practice a complete beginner-friendly data workflow:

- Collect historical stock data with Python.
- Scrape company revenue tables from web pages.
- Clean and prepare financial datasets for visualization.
- Build dashboard-style charts that show stock price and revenue over time.

## Tools and Libraries Used

- Python
- Jupyter Notebook
- pandas
- yfinance
- requests
- BeautifulSoup
- Plotly

## Data Sources

- Historical stock price data from Yahoo Finance through the `yfinance` Python library.
- Company revenue data scraped from web pages used in the IBM course assignment.

## Key Tasks Performed

- Extracted Tesla historical stock data using `yfinance`.
- Scraped Tesla revenue data with `requests` and `BeautifulSoup`.
- Extracted GameStop historical stock data using `yfinance`.
- Scraped GameStop revenue data with `requests` and `BeautifulSoup`.
- Cleaned revenue values by removing currency symbols, commas, and empty values.
- Created interactive Plotly visualizations comparing share price and revenue.

## Main Outputs

- [stock_revenue_dashboard_analysis.ipynb](stock_revenue_dashboard_analysis.ipynb): Jupyter Notebook containing the full analysis workflow.
- Interactive Plotly charts for:
  - Tesla historical share price and revenue.
  - GameStop historical share price and revenue.

## How to Run the Project

1. Clone this repository.
2. Open the notebook in Jupyter Notebook, JupyterLab, VS Code, or another notebook environment.
3. Install the required Python libraries if they are not already available:

   ```bash
   pip install pandas yfinance requests beautifulsoup4 plotly nbformat
   ```

4. Run the notebook from top to bottom:

   ```text
   stock_revenue_dashboard_analysis.ipynb
   ```

## Limitations

- This is an educational project, not an investment analysis tool.
- The notebook depends on live external data sources, so results may change or fail if websites, APIs, or table structures are updated.
- The analysis is limited to Tesla and GameStop.
- The visualizations are exploratory and do not include statistical modeling, forecasting, or financial recommendations.

## What I Learned

- How to retrieve historical market data with `yfinance`.
- How to scrape and parse HTML tables with `requests` and `BeautifulSoup`.
- How to clean financial text data for analysis.
- How to combine stock price and revenue data in dashboard-style visualizations.
- How to present a small data analysis project clearly for GitHub.

## Suggested GitHub Repository Description

Python project analyzing historical stock prices and company revenue data, with dashboard visualizations using Plotly.

## Suggested GitHub Topics

`python` `finance` `data-analysis` `stock-market` `web-scraping` `yfinance` `plotly` `dashboard`
