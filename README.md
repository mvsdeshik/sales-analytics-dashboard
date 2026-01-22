# Sales Analytics Dashboard

## Overview
This project analyzes retail sales data to uncover trends, key performance indicators (KPIs), and actionable business insights.  
The analysis pipeline includes data cleaning, aggregation, cloud storage, and interactive visualization.

## Tech Stack
- Python (pandas)
- SQL (SQLite)
- AWS S3
- Power BI
- Excel

## Dataset
- ~49,000 synthetic retail sales records
- Fields include order date, region, product, category, revenue, and orders

## Project Workflow
1. Cleaned and transformed raw sales data using Python (pandas)
2. Calculated KPIs such as Total Revenue, Total Orders, and Average Order Value
3. Stored curated analytics outputs in AWS S3
4. Built an interactive Power BI dashboard to visualize trends and performance

## Power BI Dashboard
![Sales Dashboard](images/dashboard_preview.png)

## Key Insights
- Sales show consistent growth over time with seasonal patterns
- Top products contribute a significant share of total revenue
- Certain regions outperform others consistently
- Electronics category dominates overall revenue

## Repository Structure
```text
sales-analytics-dashboard/
│
├── images/
│   └── dashboard_preview.png
├── notebooks/
├── data/
└── README.md
