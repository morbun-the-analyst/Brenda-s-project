# Retail Customer Segmentation & Revenue Analysis for 2010-2014

## Table of contents
- [Project Description Summary](#project-description)
- [Project Overview](#project-overview)
- [Executive Summary](#executive-summary)
- [Data Description](#data-description)
- [Customer Report ERD](#customer-report-erd)
- [Insights Deep Dive](#insights-deep-dive)
- [Visuals](#visuals)
- [Recommendations](#recommendations)
- [Clarifying Questions](#clarifying-questions)
- [caveats](#caveats)
## Project Description Summary
**Duration**: 3weeks

**Tools**: Excel (PivotTables, PivotCharts)

**Skills Demonstrated**: EDA, segmentation, KPI analysis, Excel visualization, business storytelling

**Key Metrics Used**: Total Sales, Recency, AOV, Monthly Spend


### Project Background

As a junior data analyst aspiring to break into tech, I worked on a simulated sales data project to mimic a real retail business scenario. The objective was to segment the customer data in sql and  analyze customer behavior across different segments and age groups using Excel—focusing on revenue drivers, customer lifetime metrics, and purchase behavior.

### Executive  Summary
Performed an end-to-end exploratory data analysis on a structured customer dataset using SQL to uncover key behavioral and purchasing patterns. Generated a customer-level report view by calculating KPIs such as recency, average order value, and average monthly spend. Segmented customers by age group and lifecycle value (New, Regular, VIP) to drive better targeting strategies.I then used Excel PivotTables and PivotCharts (clustered column and stacked column) to explore patterns in the data. The analysis identified New Customers aged 50+ as the highest contributors to recent revenue. However, VIP customers had the lowest recency, suggesting stronger brand loyalty. Recommendations were made on targeting retention campaigns based on these insights.

### Data Description
- Source: Simulated retail sales data from a self-created SQL project

- Tables used:

  fact_sales: contains order-level transaction details

  dim_customers: contains customer demographic data

 - Total records: ~18,483 rows

- Key variables:

  order_number, order_date, sales_amount, quantity, product_key

  customer_key, customer_number, first_name, last_name, birthdate

- Key derived metrics:

  Customer age, recency, average order value (AOV), monthly spend, lifespan

- Customer segments created based on:

  Sales performance and duration of activity (VIP, Regular, New)

  Age groups (e.g., 20–29, 30–39, 50+)

Purpose: To analyze customer behaviors, uncover high-value segments, and generate business recommendations

## Customer Report ERD
<img src="https://github.com/morbun-the-analyst/Brenda-s-project/blob/main/SALES%20ERD.png?raw=true" alt="SALES ERD" width="250"/>

### Insights Deep Dive
Using Excel, I analyzed the following:
1. Revenue Contribution
-	New Customers: 37% of total sales
-	VIP Customers: 36% of total sales
-	Regular Customers: 25% of total sales
2. Age Group Contribution
-Customers aged 50+ contributed the highest revenue (66% of total sales)
3. Recency
- VIPs had the lowest recency of 23k months, indicating recent engagement
-	New customers had higher recency 200k months , suggesting they may churn if not retained
4. Average Order Value (AOV) & Monthly Spend
-	New Customers had the highest AOV and monthly spend of 52% and 89% repectively , showing potential for upselling or loyalty programs.

  ### visuals



