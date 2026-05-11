# Time Series Analysis 2026: Capstone Project 📈

This repository contains the code, analysis, and final report for the **Time Series Analysis 2026 Capstone Project**, conducted in collaboration with the Consulting & Analytics Club (IIT Guwahati) and StockGro.

## 🎯 Project Objective
The goal of this project is to apply time series forecasting and quantitative analysis techniques to build a data-driven stock portfolio. The strategy was executed on the StockGro virtual trading simulator using a starting capital of ₹10,00,000.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Source:** Yahoo Finance API (`yfinance`)
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `statsmodels`, `scikit-learn`
* **Execution Environment:** Jupyter Notebook

## 📊 Methodology
1. **Stock Universe:** Selected a diverse basket of 5 NSE stocks (RELIANCE, TCS, HDFCBANK, SUNPHARMA, MARUTI).
2. **Forecasting Models:** Implemented and compared **ARIMA** and **Exponential Smoothing (Holt-Winters)** to predict 5-day future returns.
3. **Volatility Analysis:** Calculated rolling 30-day standard deviations to assess the near-term risk profile of each asset.
4. **Portfolio Allocation:** Blended two quantitative strategies to allocate capital:
   * *Volatility-Aware Sizing* (50%) - prioritizing lower-risk assets.
   * *Forecast-Guided Allocation* (50%) - prioritizing assets with higher expected returns.

## 🏆 Results
During the simulated trading window, the portfolio strategy successfully yielded a positive return:
* **Initial Investment:** ₹10,00,000
* **Final Portfolio Value:** ₹1,022,164.02
* **Net Profit:** +₹22,164.02 (+2.22%)

## 📁 Repository Contents
* `capstone_project.ipynb`: The complete Python notebook containing the data pipeline, modeling, and portfolio construction.
* `capstone_project.html`: An HTML export of the notebook for easy viewing.
* `capstone_project_report.docx`: The final comprehensive 10-page project report detailing the methodology and reflections.

---
*Disclaimer: This project was built for educational and simulation purposes. The forecasts and models do not constitute real financial advice.*
