# Task 3: Business KPI Dashboard

Interactive dashboard (single `index.html`, no dependencies) for churn, retention, revenue risk and tenure. Data is embedded from `customer_churn_sample.csv`.

**Live demo:** see the link in the top-level README (GitHub Pages), or download `index.html` and open it in a browser.

## KPI definitions
- **Churn rate** = churned customers / customers in the selection
- **Retention rate** = 1 - churn rate
- **Revenue at risk** = monthly charges of churned customers (lost MRR), also shown as a share of total monthly revenue and x12 per year. The data has no active/at-risk status, so this is revenue already lost.
- **Tenure KPIs** = average tenure in months: all, churned, retained

## Features
- Filters: contract, tenure band (0-6, 7-12, 13-24, 25+ months), payment method; reset button
- Charts: churn rate by contract / tenure band / payment method, revenue at risk by plan, average tenure churned vs retained
- Colour-blind-safe palette (blue/orange), value labels on every bar, light and dark mode
- A written insight under each chart that updates with the filters

## Limitations
Only 15 synthetic customers, so figures are indicative, not statistically reliable.
