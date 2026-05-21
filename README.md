About
This project identifies key drivers of customer churn in a bank, builds predictive models to flag high-risk customers, and visualizes findings through interactive Power BI dashboards — enabling targeted retention strategies.
Dataset: 10,000 customers across France, Spain, and Germany · 14 features including demographics, engagement, and balance data.

Workflow
1
Exploratory Data Analysis — Churn distribution, demographic trends, factor analysis per feature
2
Feature Engineering — Risk segments, engagement scores, balance-to-salary ratio, age groups
3
Predictive Modeling — Logistic Regression, Random Forest, Gradient Boosting with ROC-AUC evaluation
4
MySQL Integration — Schema creation, data push via SQLAlchemy, analytical query layer
5
Power BI Dashboard — Churn KPIs, segment breakdowns, risk customer table with slicers


Key Findings
· Inactive members churn at ~2× the rate of active ones
· Customers aged 45–60 show highest churn
· Germany has the highest churn rate by country
· 3–4 product holders churn disproportionately
