# Project 1: Data Collection and Initial Analysis of Stock Market Data

## Project Overview

This project presents an Exploratory Data Analysis (EDA) of historical stock market data from 1970 to 2018. The objective was to clean, explore, summarize, and visualize stock price data to identify long-term trends, compare market behavior across decades, and gain insights into stock performance by sector.

The project was completed using Python in Google Colab as part of a Data Analytics course assignment.

---

## Objectives

The main objectives of this project were to:

- Load and explore historical stock datasets.
- Clean and prepare the data for analysis.
- Segment stock prices by decade.
- Merge stock price data with company information.
- Calculate descriptive statistics.
- Create visualizations to identify trends and patterns.
- Develop hypotheses for future financial analysis.

---

## Dataset

The project uses two datasets:

- **historical_stock_prices.csv** – Daily stock prices including Open, High, Low, Close, Volume, Date, and Ticker.
- **historical_stocks.csv** – Company information including ticker symbols, company names, sectors, and industries.

For faster processing in Google Colab, a sample of approximately 1.5 million stock price records was used.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib

---

## Project Workflow

The project followed these steps:

1. Load the datasets.
2. Inspect the data structure.
3. Check for missing values.
4. Remove duplicate records.
5. Convert the Date column to datetime format.
6. Create a Decade column.
7. Merge stock prices with company information.
8. Generate summary statistics.
9. Create visualizations.
10. Analyze trends and summarize findings.

---

## Visualizations

The notebook includes several visualizations, including:

- Average Monthly Closing Price Trend
- Trading Volume Distribution (Log Transformed)
- High Price Boxplot by Decade
- Low Price Boxplot by Decade
- Sector-Level Summary Analysis

---

## Key Findings

Some of the key findings include:

- The datasets contained no missing values or duplicate records.
- Stock prices generally increased over the decades.
- The 2000s showed the highest price variability.
- Trading volume was highly skewed, making a logarithmic transformation useful for visualization.
- The Health Care sector recorded the highest average closing prices.
- Technology and Finance sectors showed relatively high trading activity.

---

## Future Work

Future improvements could include:

- Predicting future stock prices using Machine Learning.
- Comparing stock performance across industries.
- Performing time-series forecasting.
- Building interactive dashboards using Plotly or Power BI.
- Analyzing stock returns and investment risk.

---

## Repository Contents

```
Project_1.ipynb
README.md
Technical_Report.pdf
historical_stock_prices.csv
historical_stocks.csv
```

---

