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

## Results

### Portfolio Growth

![Portfolio Growth](results/portfolio_growth.png)

### Drawdown Analysis

![Drawdown](results/drawdown.png)

### Correlation Matrix

![Correlation Heatmap](results/correlation_heatmap.png)

### Risk Contribution

![Risk Contribution](results/risk_contribution.png)

## Methodology

The analysis uses historical daily market data to estimate portfolio returns, volatility, correlations, Value at Risk, Expected Shortfall, and drawdown characteristics.

Portfolio risk is evaluated using both statistical measures and scenario-based stress testing.

## Risk Management Framework

The project follows a simplified risk management framework:

1. Data Collection
2. Portfolio Construction
3. Performance Measurement
4. Risk Measurement
5. Risk Attribution
6. Stress Testing
7. Risk Interpretation

## Limitations

The analysis has several limitations:

- Historical data may not represent future market conditions.
- VaR estimates depend on the selected methodology and confidence level.
- Stress-testing scenarios are hypothetical.
- Correlations may change significantly during periods of market stress.
- Transaction costs and liquidity effects are not explicitly modeled.

## Future Improvements

Potential extensions include:

- Monte Carlo simulation
- GARCH volatility modeling
- Fama-French factor analysis
- Dynamic portfolio optimization
- Conditional Value at Risk optimization
- Interactive Streamlit dashboard
- Real-time market data integration

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
└── results/
