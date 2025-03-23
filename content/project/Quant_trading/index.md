---
title: "Quant Strategy & Portfolio Optimization Project"
summary: "An in-depth quantitative strategy project that implements long and short equity strategies—based on growth, momentum, and valuation criteria—to construct a market-neutral portfolio. The project features rigorous backtesting, screening, and portfolio optimization analyses."
date: 2025-03-22
tags: ["Quantitative Strategy", "Portfolio Optimization", "Finance", "Backtesting", "Market Neutral"]
---

## Project Overview

This project develops a quantitative equity strategy that combines a long position based on growth and momentum with a short position driven by valuation and reversal signals. The aim is to construct a market-neutral portfolio that generates excess returns while minimizing systematic risk.

## Strategy Description & Rationale

### Long Strategy: Growth and Momentum
- **Objective:** Identify large-cap stocks with strong earnings growth and robust price momentum.
- **Method:**  
  - Select stocks in the top 10th percentile for earnings growth over the past year.  
  - Among these, choose stocks with the highest percentage change in closing price within each industry.
- **Rationale:** Companies exhibiting consistent financial improvement and price momentum are likely to continue their upward trend.

### Short Strategy: P/E and Reversal
- **Objective:** Short overvalued stocks that show signs of a downward trend.
- **Method:**  
  - Screen for stocks with high P/E ratios in the top 20th percentile within their industry.
  - Further filter for stocks whose closing price is below their 1-year moving average.
  - Apply an RSI filter (RSI > 60) to capture overbought conditions.
- **Rationale:** Stocks that are overextended in price and underperforming relative to their valuation are likely to experience reversals.

### Backtesting & Portfolio Performance

The strategy was backtested using historical data, with key metrics summarized as follows:
- **Annualized Return:** 15.43%
- **Annualized Standard Deviation:** 28.93%
- **Annualized Sharpe Ratio:** 0.65
- **Beta:** -0.07 (indicating near market neutrality)
- **Maximum Drawdown:** 46.17%

These results suggest that the portfolio achieves market neutrality and generates excess returns, with the long and short strategies effectively complementing one another.

## Supporting Documents

Below are direct links to the key files that support this analysis:

- [Backtest - Long.xls](/my_website/uploads/Backtest%20-%20Long.xls)
- [Backtest - Short.xls](/my_website/uploads/Backtest%20-%20Short.xls)
- [Portfolio.xlsx](/my_website/uploads/Portfolio.xlsx)
- [Quant Project Presentation.pptx](/my_website/uploads/Quant%20Project%20Presentation.pptx)
- [Quant Strategy Report.pdf](/my_website/uploads/Quant%20Strategy%20Report.pdf)
- [Screeners - Long.png](/my_website/uploads/Screeners%20-%20Long.png)
- [Screeners - Short.png](/my_website/uploads/Screeners%20-%20Short.png)

## Future Directions

- **Dynamic Rebalancing:** Explore periodic rebalancing strategies to adjust the portfolio in response to market changes.
- **Advanced Risk Metrics:** Incorporate additional metrics (e.g., Calmar ratio) for a more comprehensive risk assessment.
- **Deployment:** Develop an API or dashboard for real-time monitoring and adjustment of the strategy.

## Conclusion

By combining a long strategy based on growth and momentum with a short strategy focused on valuation and reversal, this project demonstrates a robust approach to portfolio optimization and market neutrality. The backtesting results and supporting analyses provide valuable insights for constructing a diversified portfolio that effectively manages risk.
