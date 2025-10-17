
# 📊 Smart Volatility Forecasting & Momentum Strategy
A quantitative research project demonstrating **volatility forecasting with GARCH models** and **risk-adjusted trading strategies using momentum factors**.

---

## 💡 Motivation
This project explores the practical application of volatility forecasting and momentum strategies in financial markets. It demonstrates a **modular, reproducible workflow** for risk-adjusted trading and provides insights into market dynamics. The goal is to showcase **real-world quantitative research methods** used in hedge funds.

---

## 📝 Project Overview
This project demonstrates a **quantitative research pipeline** for building a **risk-adjusted trading strategy** using **volatility forecasting (GARCH models)** and **momentum factors**. Key components include:

- **Data Collection & Cleaning:** Historical daily stock prices for liquid US equities.
- **Volatility Modeling:** GARCH-family models (**GARCH, EGARCH, TGARCH**) to forecast future volatility.
- **Factor Construction:** Momentum signals calculated from historical returns.
- **Risk-Adjusted Strategy:** Dynamic position sizing using predicted volatility and momentum filters.
- **Backtesting & Evaluation:** Performance assessed with **Sharpe ratio**, **Sortino ratio**, **max drawdown**, turnover, and robustness tests.

---

## 🔑 Key Features
- Reproducible, modular workflow for research and backtesting
- Out-of-sample validation and robustness across market regimes
- Clear visualization of returns, risk, and strategy signals
- Designed to be scalable and re-usable for additional assets or timeframes

---

## 🎯 Purpose
This project showcases the **full research cycle used in hedge funds** — hypothesis formulation, data processing, statistical modeling, strategy construction, and performance evaluation — implemented in **Python and R**.

---

## 🛠 Technologies / Tools Used
- **Python, R, Jupyter Notebook**
- **pandas, numpy, statsmodels, matplotlib, seaborn**
- **GitHub** for version control and project documentation

---

## 📁 Repo Structure


```volatility_project/
├─ data/       # folder to store raw & processed stock price data
├─ notebooks/  # folder for Jupyter notebooks (your analysis and modeling)
├─ outputs/    # folder for plots, results, metrics
├─ README.md   # this file, containing project overview```

