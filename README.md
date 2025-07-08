# TSLA-GME Analysis

Analyze and visualize Tesla (TSLA) and GameStop (GME) stock performance alongside their revenue trends using Python.

## Overview

This project extracts historical stock data using the `yfinance` library and scrapes quarterly revenue data from Macrotrends using `BeautifulSoup`. It then generates dual-axis plots using `matplotlib` to compare each company’s stock price with its revenue over time.

## Contents

- `TSLA_GME_Analysis.ipynb` – Main Jupyter notebook with code and graphs
- `make_graph()` – Custom function to visualize stock vs. revenue
- Tesla and GameStop data cleaning and transformation
- Dual-axis revenue vs stock price charts

## Technologies Used

- Python
- [yfinance](https://pypi.org/project/yfinance/)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
- matplotlib
- pandas
- requests

## Example Output

- Tesla: Stock price vs revenue trend
- GameStop: Stock price vs revenue trend

## Purpose

To explore the relationship between a company’s financial performance (revenue) and its market performance (stock price) over time using publicly available data and Python tools.

## How to Run

1. Clone the repo  
2. Install required packages:  
   ```bash
   pip install yfinance pandas matplotlib requests beautifulsoup4

