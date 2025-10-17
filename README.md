
# 📊 Smart Volatility Forecasting & Momentum Strategy
Exploring GARCH models and momentum signals to understand risk-adjusted trading in a reproducible research workflow.

---

## 💡 Motivation
I’ve always been fascinated by how market volatility behaves and how it interacts with trends.  
This project started as a way to experiment with **GARCH-family models** while exploring how **momentum signals** could help create robust, risk-adjusted trading strategies.  
The goal is not just to build a model, but to **understand patterns, test assumptions, and explore market dynamics**.

---

## 📝 Project Overview
This project demonstrates a **quantitative research pipeline** for building a **risk-adjusted trading strategy** using **volatility forecasting** and **momentum factors**. Key components include:

- **Data Collection & Cleaning:** Historical daily stock prices for liquid US equities.  
- **Volatility Modeling:** Tested **GARCH, EGARCH, TGARCH** to capture volatility spikes, asymmetry, and persistence.  
- **Factor Construction:** Built momentum signals over multiple lookback periods to explore predictive power.  
- **Risk-Adjusted Strategy:** Applied dynamic position sizing using predicted volatility and momentum filters.  
- **Backtesting & Evaluation:** Evaluated performance with **Sharpe ratio**, **Sortino ratio**, max drawdown, turnover, and robustness tests across different time periods.  

> This approach mirrors real-world research: **hypothesize, implement, test, and iterate**.

---

## 🔑 Key Features
- Modular and reproducible workflow for analysis and backtesting.  
- Out-of-sample validation and robustness checks across market regimes.  
- Clear visualization of returns, risk, and strategy signals.  
- Designed to be **scalable and re-usable** for additional assets, markets, or alternative models.  

---

## 🎯 Purpose
The project is a **sandbox for exploring quantitative finance models**. It allows for experimentation with volatility forecasting, momentum factors, and risk-adjusted strategies while providing a **reusable pipeline** for further research.  
It showcases **real-world quantitative research methods** used in hedge funds — hypothesis formulation, data processing, statistical modeling, strategy construction, and performance evaluation — implemented in **Python and R**.

---

## 🛠 Technologies / Tools Used
- **Python, R, Jupyter Notebook**  
- **pandas, numpy, statsmodels, matplotlib, seaborn**  
- **GitHub** for version control and documentation  

---

## 📁 Repo Structure
```volatility_project/
├─ data/       # raw & processed stock price data
├─ notebooks/  # step-by-step notebooks for analysis and modeling
├─ outputs/    # plots, results, metrics, and observations
├─ README.md   # this file, describing the project
