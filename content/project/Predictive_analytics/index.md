---
title: "Optimizing Customer Acquisition Strategies Using Predictive Analytics"
summary: "A group project by Sophia Mei, Alex Ng, Ying Qing, and Laurie Ye that uses predictive analytics to optimize customer acquisition costs for Convenient Food Mart. The project applies data cleaning, regression modeling, and variable selection techniques to develop an efficient model for customer targeting."
date: 2025-03-22
tags: ["Predictive Analytics", "Customer Acquisition", "Regression", "Marketing", "Data Science"]
---

## Project Overview

Convenient Food Mart faces high customer acquisition costs due to inefficient targeting. In this project, our team (Sophia Mei, Alex Ng, Ying Qing, and Laurie Ye) applied predictive analytics to a customer dataset to identify the key demographic and behavioral factors that drive profitable customer acquisition. Our goal is to build an efficient model to estimate customer acquisition costs, thereby enabling more precise and cost-effective marketing strategies.

## Data & Preprocessing

- **Dataset:**  
  The analysis is based on a customer dataset containing variables such as marital status, gender, total children, education level, member card status, occupation, homeownership, average cars at home, and average yearly income.
  
- **Data Cleaning & Transformation:**  
  - Irrelevant and duplicate columns were dropped.
  - Categorical variables (e.g., "Home," "Education," "Member Card") were converted into dummy variables.
  - Missing values were dropped to ensure data robustness.
  - Box-Cox transformations were applied to stabilize variance in key predictors.

## Modeling Approach

### Linear Regression
- **Baseline Model:**  
  A linear regression model was developed to estimate customer acquisition costs.
- **Box-Cox Transformation:**  
  Applied to improve model fit by reducing skewness.
- **Evaluation:**  
  Performance was measured using error metrics such as RMSE, MAE, MPE, and MAPE—evaluated on both the original and Box-Cox transformed data.

### Regression Trees
- **Decision Tree Modeling:**  
  A regression tree was constructed to capture non-linear relationships.
- **Pruning:**  
  Pruned trees were compared with unpruned versions to reduce overfitting, resulting in lower error metrics.

### Model Comparison
- The performance of the linear regression models (with and without Box-Cox transformation) was compared with the regression tree approach. Error metrics and residual analysis were used to determine which model provided the best predictive accuracy.

## Key Findings

- **Variable Importance:**  
  The analysis identified that variables such as average yearly income, number of cars at home, and demographic factors play a significant role in determining customer acquisition costs.
- **Model Performance:**  
  The Box-Cox transformed linear regression model and the pruned regression tree both showed improvements over the baseline model.
- **Marketing Insights:**  
  The model can be applied during the promotion planning stage to estimate media costs and better target customer segments, potentially reducing overall acquisition costs.

## Repository Structure

- **ISOM 455 Final Project.pdf:**  
  The final project report detailing the business problem, methodology, and key findings.
- **Data Spreadsheet**  
  The spreadsheet includes all the data used in this project.

## Documents

- [ISOM 455 Final Project Report (PDF)](/my_website/uploads/ISOM%20455%20Final%20Project.pdf)
- [Data (CSV)](/my_website/uploads/Media.csv)


## Future Directions

- **Enhanced Variable Analysis:**  
  Incorporate additional predictors (e.g., store data, promotion type) to refine the model.
- **ROI Integration:**  
  Pair customer acquisition costs with Customer Lifetime Value (CLV) for a more comprehensive analysis.
- **Deployment:**  
  Develop an API or dashboard for real-time prediction to support marketing strategy adjustments.

## Conclusion

By applying a rigorous data cleaning process, variable selection, and multiple regression techniques, this project provides a data-driven approach to optimizing customer acquisition. The insights derived from the model can help Convenient Food Mart reduce marketing spend and improve customer targeting, leading to more efficient acquisition strategies.
