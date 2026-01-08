# Project Background
The Mexico Toy Sales project was created to build a simple yet effective KPI reporting dashboard for a fictional toy retail chain operating across Mexico.
The objective is to track orders, revenue, and profit, and explore high-level trends across time, product categories, and store locations.
# Dashboard Used
- Power BI Desktop
- Relational Data Model (Star Schema)
- DAX Measures
- KPI Cards, Slicers, Bar & Line Charts
# Data Structure
## Data Sources (CSV Files): 
- <a href = "https://github.com/mizanur-analytics/mexico-toy-sales-powerbi/blob/main/sales.csv">sales</a>
- <a href = "https://github.com/mizanur-analytics/mexico-toy-sales-powerbi/blob/main/stores.csv">stores</a>
- <a href = "https://github.com/mizanur-analytics/mexico-toy-sales-powerbi/blob/main/products.csv">products</a>
- <a href = "https://github.com/mizanur-analytics/mexico-toy-sales-powerbi/blob/main/calendar.csv">calendar</a>
## Key Data Preparation Steps
- Reviewed columns, data types, and null values
- Identified primary and foreign keys
- Added calculated date fields:
  - Start of Month
  - Start of Week
## Data Model
- Star schema with sales as the fact table
- One-to-many relationships to:
  - Products
  - Stores
  - Calendar
- Foreign keys hidden from report view
## Questions (KPIs)
- How many orders were placed?
- What is the total revenue and total profit?
- How do sales and profits trend over time?
- Which product categories generate the most orders?
- How does performance vary by store location?
## Process
1.	Connected Power BI to all source CSV files
2.	Profiled data for quality, completeness, and accuracy
3.	Built a relational star schema data model
4.	Created calculated columns for revenue and profit
5.	Defined DAX measures for key KPIs
6.	Designed an interactive dashboard with filters and trends
# Dashboard
## Key Dashboard Components
- KPI Cards:
  - Total Orders (current month)
  - Total Revenue (current month)
  - Total Profit (current month)
- Monthly trend indicators for each KPI
- Store location slicer
- Bar chart: Total Orders by Product Category
- Line chart: Total Revenue over time (date hierarchy)
![Toy_Store_Power BI](https://github.com/user-attachments/assets/9d76914e-6a28-4408-a7b9-6c49e291acb4)
# Executive Summary
## Overview of Findings
- Sales performance varies significantly by product category
- Revenue and profit follow consistent seasonal patterns
- Certain categories drive high order volume but lower margins
## Sales Trends
- Monthly revenue shows clear upward and downward cycles
- Promotional or seasonal effects can be inferred from spikes
## Product Performance
- A small number of product categories contribute a large share of total revenue
- Profitability does not always align with order volume
# Project Insights
-	Quantified Value:
Identified top-performing categories contributing the majority of revenue.
-	Business Metric Impact:
Profit analysis highlights opportunities to optimize pricing and inventory.
-	Trend Story:
Revenue growth is driven more by timing and category mix than by store count alone.
![Toy_Store_Power BI_2](https://github.com/user-attachments/assets/8277862a-d5f8-456d-834c-0458fb59e2c3)
# Conclusion
The Mexico Toy Sales dashboard provides a clear, executive-level view of business performance using reliable KPIs and intuitive visuals. It enables fast, data-driven decision-making.
## Recommendations
-	Focus marketing efforts on high-margin product categories
-	Investigate low-profit, high-volume products for pricing optimization
-	Extend the model with inventory turnover or forecasted demand metrics
