# volatility-forecasting-hedgefund
Volatility forecasting and risk-adjusted strategy modeling using GARCH and momentum factors.
📊 Smart Volatility Forecasting & Momentum Strategy

Project Overview:
This project demonstrates a quantitative research pipeline for building a risk-adjusted trading strategy using volatility forecasting (GARCH models) and momentum factors. It is designed to mirror real-world hedge fund research, with a focus on:
	•	Data Collection & Cleaning: Historical daily stock prices for liquid US equities.
	•	Volatility Modeling: GARCH-family models (GARCH, EGARCH, TGARCH) to forecast future volatility.
	•	Factor Construction: Momentum signals calculated from historical returns.
	•	Risk-Adjusted Strategy: Dynamic position sizing using predicted volatility and momentum filters.
	•	Backtesting & Evaluation: Performance assessed with Sharpe ratio, Sortino ratio, max drawdown, turnover, and robustness tests.

Key Features:
	•	Reproducible, modular workflow for research and backtesting
	•	Out-of-sample validation and robustness across market regimes
	•	Clear visualization of returns, risk, and strategy signals
	•	Designed to be scalable and re-usable for additional assets or timeframes

Purpose:
This project showcases the full research cycle used in hedge funds — hypothesis formulation, data processing, statistical modeling, strategy construction, and performance evaluation — all implemented in Python and R.
Repo Structure (high-level):
volatility_project/
├─ data/           # raw & processed stock price data
├─ notebooks/      # Jupyter notebooks for each step
├─ outputs/        # plots, results, metrics
├─ README.md       # project overview
