# IBM Python Project for Data Science - Stock Data Dashboard

## Project Overview
This repository contains the final project for the **Python Project for Data Science** course offered by IBM on Coursera. The goal of this project is to extract financial data, specifically historical stock share prices and quarterly revenue, and visualize it in a dashboard format to identify investing patterns or trends.

## Objectives
In this project, the following tasks were completed:
1. **Extracting Stock Data:** Used the `yfinance` library to extract historical stock data for Tesla (TSLA) and GameStop (GME).
2. **Web Scraping Revenue Data:** Used the `requests` and `BeautifulSoup` libraries to scrape historical quarterly revenue data from web pages for both companies.
3. **Data Cleaning:** Processed the scraped HTML tables into Pandas DataFrames, removing null values and formatting string currencies into usable numerical data.
4. **Data Visualization:** Utilized `matplotlib` to plot the historical share price alongside the historical revenue for both Tesla and GameStop up to June 2021.

## Technologies & Libraries Used
* **Python**
* **Pandas** (Data manipulation and analysis)
* **yfinance** (Extracting market data from Yahoo Finance)
* **BeautifulSoup** (HTML parsing and web scraping)
* **Requests** (HTTP library for downloading web pages)
* **Matplotlib** (Data visualization)

## Files in this Repository
* `Revenue Data and Building a Dashboard.ipynb`: The main Jupyter Notebook containing the Python code, data extraction steps, and generated graphs.

## Acknowledgments
* Course: [Python Project for Data Science](https://www.coursera.org/learn/python-project-for-data-science) by IBM on Coursera.
