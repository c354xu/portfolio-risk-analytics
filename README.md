# Portfolio Risk Analytics & Stress Testing

## Overview

This project develops a Python-based portfolio risk analytics framework designed to evaluate investment performance, quantify financial risk, and assess portfolio resilience under different market stress scenarios.

The project applies concepts from financial analysis, portfolio management, statistics, and risk management.

## Objectives

- Analyze historical portfolio performance
- Measure portfolio risk and volatility
- Calculate Value at Risk (VaR)
- Estimate Expected Shortfall (CVaR)
- Analyze portfolio drawdowns
- Examine correlations between assets
- Measure portfolio risk contribution
- Conduct scenario-based stress testing
- Visualize portfolio performance and risk metrics

## Portfolio

The initial portfolio consists of five large-cap U.S. companies:

| Ticker | Company | Sector | Weight |
|--------|---------|--------|--------|
| AAPL | Apple Inc. | Technology | 20% |
| MSFT | Microsoft Corp. | Technology | 20% |
| JPM | JPMorgan Chase & Co. | Financials | 20% |
| XOM | Exxon Mobil Corp. | Energy | 20% |
| JNJ | Johnson & Johnson | Healthcare | 20% |

The portfolio uses an equal-weight allocation.

## Key Risk Metrics

- Annualized Return
- Annualized Volatility
- Sharpe Ratio
- Maximum Drawdown
- Value at Risk (VaR)
- Expected Shortfall (CVaR)
- Correlation
- Portfolio Risk Contribution

## Stress Testing

The project evaluates portfolio sensitivity under adverse market scenarios, including:

- Broad market decline
- High-volatility environment
- Sector-specific shocks
- Interest-rate-related scenarios

## Technology Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- yfinance
- Jupyter Notebook

## Project Structure

```text
portfolio-risk-analytics/
│
├── README.md
├── requirements.txt
│
├── data/
│
├── notebooks/
│   ├── 01_data_collection.ipynb
│   ├── 02_portfolio_analysis.ipynb
│   ├── 03_risk_analysis.ipynb
│   └── 04_stress_testing.ipynb
│
├── src/
│   ├── data.py
│   ├── portfolio.py
│   ├── risk.py
│   └── visualization.py
│
└── results/
