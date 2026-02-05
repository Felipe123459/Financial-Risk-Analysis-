# Financial Risk Analysis Dashboard 
## Overview

This project analyzes the risk and return characteristics of five publicly traded stocks (AAPL, JNJ, JPM, WMT, XOM). The dashboard evaluates performance using financial metrics such as cumulative return, volatility, and Sharpe ratio to compare risk-adjusted returns 
across assets.

---
## Business Objectives

- Compare stock performance on a risk-adjusted basis
- Identify periods of increased volatility
- Evaluate returns relative to benchmark targets
- Support portfolio allocation decisions

---

## Dataset Description

Source: Kaggle 

Assets: AAPL, JNJ, JPM, WMT, XOM

Time Period: 2015–2025

Key Fields: Date, Open, High, Low, Close, Volume, Daily Return

---

## Methodology

- Calculated daily returns from adjusted close prices
- Computed rolling 30-day volatility
- Calculated cumulative returns by asset
- Derived Sharpe ratio for performance comparison
- Aggregated results by month and year for trend analysis

---

## Key Findings

- Technology stocks showed higher returns with higher volatility
- Consumer staples (WMT) demonstrated lower volatility and steadier growth
- Periods of market stress aligned with volatility spikes
- Risk-adjusted performance varied significantly by sector

---

## Tools & Technologies

- Power BI
- DAX (time intelligence, rolling metrics)
- Power Query
- Excel / Yahoo Finance API

---

## Dashboard Highlights

- Risk vs Return scatter plot for asset comparison
- Rolling volatility trends by stock
- Cumulative return performance over time
- Sharpe ratio compared against benchmark
- Interactive slicers for date and stock selection

---

## Business Recommendations

- Favor assets with strong risk-adjusted returns for long-term allocation
- Monitor volatility spikes as potential rebalancing signals
- Diversify across sectors to reduce overall portfolio risk

---

## Future Improvements

- Add portfolio optimization (mean-variance allocation)
- Include macroeconomic indicators
- Incorporate drawdown and beta metrics
- Add scenario stress testing

---
