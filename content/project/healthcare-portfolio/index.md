---
title: "Pharmaceutical Industry Portfolio Optimization & Risk Analysis"
summary: "An in‐depth analysis of the pharmaceutical industry that uses portfolio optimization, CAPM, and non‐parametric risk metrics to evaluate the performance and risk characteristics of major drug manufacturers."
date: 2025-03-22
tags: ["Pharmaceuticals", "Portfolio Optimization", "CAPM", "Risk Analysis", "Finance"]
---

## Project Overview

This project examines the performance and risk profiles of leading pharmaceutical companies using a quantitative framework. By combining portfolio optimization techniques with CAPM analysis and non‐parametric risk assessments (such as Value at Risk and Expected Shortfall), the study aims to construct an optimized portfolio that maximizes risk‐adjusted returns while mitigating downside risks through diversification.

## Data & Methodology

- **Data Sources:**  
  Financial data for major drug manufacturers (e.g., Pfizer, Johnson & Johnson, AbbVie) were obtained from public sources such as Yahoo Finance. The dataset spans multiple periods to enable comparison before and during market disruptions (e.g., COVID-19).

- **Data Preparation:**  
  Raw data were cleaned to remove missing values and outliers, with appropriate transformations applied (e.g., conversion of categorical variables into dummy variables).

- **Modeling & Analysis:**  
  - **Portfolio Optimization:**  
    A tangency portfolio was constructed to maximize the Sharpe ratio, providing an “Optimal Portfolio” whose performance is compared against individual stocks.
  - **CAPM Analysis:**  
    The Capital Asset Pricing Model (CAPM) was applied using market returns from the S&P 500 and a risk-free proxy from Treasury yields to estimate beta values.
  - **Risk Metrics:**  
    Non‐parametric methods were used to compute Value at Risk (VaR) and Expected Shortfall (ES) for both the 2017–2019 and 2020–2022 periods, illustrating changes in downside risk.

## Key Findings

- **Diversification Benefits:**  
  The industry index shows lower volatility compared to individual stocks, demonstrating the risk-reducing effect of diversification.
- **Portfolio Performance:**  
  The optimized portfolio achieves a higher Sharpe ratio than individual stocks, albeit with slightly higher volatility, which is acceptable given the improved risk-adjusted returns.
- **CAPM Insights:**  
  Beta estimates reveal that individual stocks vary in market sensitivity while the optimized portfolio maintains a near market-neutral position.
- **Risk Analysis:**  
  The VaR and ES metrics highlight that, even during periods of increased market instability, the industry index remains the safest option.

## Supporting Documents

For further details on the analysis and methodology, please refer to the following documents:

- [Project Presentation.pdf](/my_website/uploads/5630%20Project%20Presentation.pdf)
- [Code Output.pdf](/my_website/uploads/Project_final.pdf)


## Repository Structure

- **Reports & Presentations:**  
  The main project report and presentation files outline the strategy, key backtest statistics, and visual summaries.
- **Python Notebook:**  
  The code file includes the entire project including data sourcing, data cleaning, modeling, and visualizations. 

## Future Directions

- **Dynamic Rebalancing:**  
  Investigate periodic rebalancing strategies to maintain optimal risk-adjusted returns.
- **Advanced Risk Metrics:**  
  Incorporate additional metrics (such as the Calmar ratio) for a more comprehensive risk assessment.
- **Deployment:**  
  Develop a dashboard or API for real-time monitoring and adjustment of the portfolio.

## Conclusion

This analysis provides a robust quantitative framework for portfolio optimization in the pharmaceutical industry. By integrating CAPM analysis with non‐parametric risk assessments, the study offers actionable insights for constructing a diversified portfolio that minimizes downside risk while capturing excess returns.
