# FP-A-Financial-Dashboard
Excel financial modeling and Power BI dashboard featuring budgeting, forecasting, variance analysis, and scenario planning.

## Power BI Dashboard Preview

This project features three interactive Power BI dashboards analyzing historical financial performance, illustrative budget variances, and forecast scenarios.

### 1. Executive Financial Overview

An executive-level summary of 2014 financial performance, including revenue, cost of goods sold, gross profit, and gross margin.

**Key Metrics:**
- Total Revenue: $92.31M
- Total COGS: $79.30M
- Gross Profit: $13.02M
- Gross Margin: 14.1%

![Executive Financial Overview]([screenshots/01_Executive_Overview.png](https://github.com/fanggmelvin/FP-A-Financial-Dashboard/blob/main/screenshots/Screenshot%202026-11-20%20062407.png))

### 2. Budget vs. Actual Analysis

Compares 2014 financial results against an illustrative budget to identify revenue variances and monthly performance trends.

**Key Findings:**
- Actual Revenue: $92.31M
- Budget Revenue: $96.93M
- Unfavorable Variance: $4.62M (-4.8%)

![Budget vs Actual](screenshots/02_Budget_vs_Actual.png)

### 3. Forecast & Scenario Analysis

An interactive forecasting dashboard comparing 2014 historical revenue against a modeled 2015 revenue forecast.

The scenario selector allows users to evaluate three revenue assumptions.

| Scenario | Forecast Revenue | Gross Profit |
|---|---:|---:|
| Bear | $138.33M | $20.75M |
| Base | $153.70M | $23.05M |
| Bull | $169.07M | $25.36M |

The model assumes a 15% forecast gross margin across all scenarios.

![Forecast and Scenarios](screenshots/03_Forecast_and_Scenarios.png)

## Methodology & Assumptions

- Historical financial performance is based on sample financial data.
- Budget figures are illustrative and are not actual company targets.
- The 2015 forecast is a modeled projection, not company-issued guidance.
- Bear and Bull scenarios adjust base forecast revenue by -10% and +10%, respectively.
- Gross margin is held constant at an assumed 15% for scenario comparison.

## Technologies Used

- **Microsoft Excel:** Financial modeling and forecasting
- **Power BI:** Interactive dashboard development
- **Power Query:** Data cleaning and transformation
- **DAX:** Financial calculations and scenario modeling

## Project Files

- `FPA_Financial_Model.xlsx` — Excel financial model
- `FPA_Executive_Dashboard.pbix` — Interactive Power BI report

## Disclaimer

This independent portfolio project uses sample financial data and illustrative financial assumptions for educational and analytical purposes.
  
