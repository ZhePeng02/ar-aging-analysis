# AR Aging & Collections Analysis

## Overview
Analysis of 2,467 invoices from a real-world accounts receivable dataset to identify late payment patterns and high-risk customers. This project replicates the type of reporting and ad-hoc analysis common in cash collection and FP&A roles.

## Tools
SQL (SQLiteOnline) · Excel

## Key Findings
- 64.5% of invoices were paid on time; 35.5% were paid late
- Average Days Sales Outstanding (DSO): 26.4 days
- Average days late among overdue invoices: 3.4 days
- Customer 6708-DPYTF had the highest overdue amount at $1,881

## Dashboard
![Dashboard](dashboard.png)

## Files
| File | Description |
|------|-------------|
| `query1_aging.csv` | Invoice-level aging classification |
| `query2_customers.csv` | Customer-level overdue summary |
| `query3_kpi.csv` | Overall KPI metrics |
| `AR_Dashboard.xlsx` | Excel dashboard with visualizations |
