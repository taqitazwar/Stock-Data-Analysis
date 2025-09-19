# Stock Data Analytics Suite

A collection of Jupyter Notebooks that demonstrate how to extract, analyze, and visualize stock market data using Python — through APIs and web scraping.

---

## What You'll Learn

- Extract real-time stock data using `yfinance`
- Scrape historical data from websites with `BeautifulSoup`
- Clean and analyze stock trends with `pandas`
- Visualize data with `matplotlib`

---

## Project Structure

| File / Folder                | Description                                           |
|-----------------------------|-------------------------------------------------------|
| `notebooks/`                | All Jupyter Notebooks for extraction + analysis       |
| `01_extract_with_yfinance`  | Uses `yfinance` API to pull live stock data           |
| `02_web_scraping_yahoo`     | Web scraping using `requests` + `BeautifulSoup`       |
| `03_visualize_stock_data`   | Line charts, trends, and comparisons using matplotlib |
| `data/`                     | (Optional) Local output files (CSV, JSON, etc.)       |
| `requirements.txt`          | Python dependencies                                   |

---

## Tech Stack

- **Language**: Python
- **Libraries**: `pandas`, `matplotlib`, `yfinance`
- **Environment**: Jupyter Notebook
- **Data Sources**: Yahoo Finance

---

## Installation

```bash
git clone https://github.com/your-username/stock-data-analytics-suite.git
cd stock-data-analytics-suite
pip install -r requirements.txt
