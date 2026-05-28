# Telecom-Customer-Churn-Analysis
Power BI dashboard analyzing customer churn for Indian telecom providers
## Dashboard Preview
![Telecom Customer Churn Dashboard]Power BI dashboard.png

## Business Problem
Customer churn is a critical challenge for telecom companies.
This project analyzes customer churn patterns across major Indian
telecom providers — Airtel, Jio, Vodafone and BSNL — to identify
key drivers of churn and provide actionable business recommendations.

## Tools Used
- Power BI Desktop — Dashboard development
- Power Query — Data cleaning and transformation
- DAX — Calculated measures and KPIs

## Dataset
- Source: Kaggle — Indian Telecom Customer Churn Dataset
- Link: https://www.kaggle.com/datasets/suraj520/telecom-churn-dataset
- Records: 244K customers
- Features: 14 columns including demographics, usage and churn status

## Data Cleaning
- Replaced negative values with 0 in calls, SMS and data usage
- Converted data usage from MB to GB
- Created derived columns — Age Group, Salary Band, Tenure Group
- Removed irrelevant column — Pincode

## Dashboard Features
- 5 KPI cards — Total Customers, Churned Customers, Churn Rate, Revenue Lost, Avg Tenure
- 8+ interactive visuals
- Bookmarks for multiple chart views
- Interactive parameter chart for city wise analysis
- Slicers for Telecom Partner and Gender filters

## Key Insights
- 1 in 5 customers are churning — overall churn rate 20.05%
- Churn is uniform across all providers — Airtel highest 20.37%, BSNL lowest 19.86%
- Gender has minimal impact — Female 20.30% vs Male 19.88%
- High salary customers drive maximum revenue loss — 2bn at risk
- Customers with 0 dependents churn most
- New customers churn most — stronger onboarding strategy needed
- Hyderabad highest churn 20.42%, Delhi lowest 19.75%

## Business Recommendations
- Strengthen new customer onboarding experience
- Survey high salary customers to understand pain points
- Introduce loyalty programs for regular customers
- Offer personalised plans for single customers
- Focus on city-wise targeted retention strategies

## Limitations
- Tenure overstated — no churn date available in dataset
- Negative values replaced with 0 — actual reason unknown
- Estimated salary used — not actual income
- Synthetic dataset — may not reflect real telecom behaviour
- No service quality or competitor data captured
