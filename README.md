# Portfolio-construction-analysis-python
Portfolio construction and performance analysis using Python. Compares equal-weight and momentum-based strategies using real market data.

## Objective
This project compares two portfolio construction approaches:
- Equal-weight portfolio
- Momentum-based strategy portfolio

The goal is to evaluate which approach delivers better risk-adjusted returns using historical market data.

## Data
- Stocks: AAPL, MSFT, AMZN, TSLA, NVDA, JPM
- Data frequency: Monthly
- Period: 2015 – 2025
- Source: Yahoo Finance

## Methodology
1. Collected historical stock price data
2. Converted daily prices to month end prices
3. Calculated monthly returns
4. Constructed:
   - Equal-weight portfolio
   - Momentum-based portfolio (top 3 stocks based on 3-month returns)
5. Rebalanced portfolios monthly
6. Evaluated performance using:
   - Annual Return
   - Volatility
   - Sharpe Ratio
   - Maximum Drawdown

## Key Results
- Momentum strategy outperformed the equal-weight portfolio in terms of returns
- However, it exhibited higher volatility and deeper drawdowns
- Demonstrates the trade-off between return and risk in portfolio construction

## Tools Used
- Python
- Pandas, NumPy
- Matplotlib

## Conclusion
Factor-based strategies such as momentum can enhance portfolio performance, but they also come with higher risk. A balanced approach is required depending on the investor’s risk tolerance.
