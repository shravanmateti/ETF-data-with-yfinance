# ETF Data with yfinance 📈

This project fetches and analyzes historical ETF data from Yahoo Finance using the [`yfinance`](https://pypi.org/project/yfinance/) Python library.  
It’s designed to make it easy to download, clean, and save ETF price history (e.g., SILVERIETF.NS) for further analysis or visualization.

---

## Features
- 📅 Fetch historical data for any ETF by ticker symbol
- ⏳ Flexible date range selection (e.g., from 1 Jan 2022 to today)
- 📊 Supports multiple intervals (daily, weekly, monthly)
- 🧹 Cleans and formats data for Excel or CSV export
- 📈 Ready for further analytics (returns, volatility, rolling averages)

---

## Requirements
- Python 3.8+
- `pandas`
- `yfinance`
- `openpyxl` (for Excel export)

Install dependencies:
```bash
pip install pandas yfinance openpyxl
