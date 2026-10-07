# BBE Sales Analytics Dashboard | Power BI

## Overview

This project is an end-to-end Power BI sales analytics solution developed to transform raw transactional data into an interactive business intelligence dashboard.

The project covers data cleaning, transformation, data modeling, DAX calculations, dashboard development, business analysis, and documentation.

## Business Objectives

- Monitor overall sales performance
- Analyze revenue by product and category
- Identify top and bottom-performing products
- Analyze customer purchasing behavior
- Evaluate sales across countries and territory groups
- Analyze promotion and discount performance
- Calculate profitability and gross margin
- Generate actionable business insights

## Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Modeling
- Star Schema
- Business Intelligence
- Data Visualization

## Data Model

The project uses a star-schema architecture consisting of:

- Fact_Sales
- Dim_Date
- Dim_Product
- Dim_Customer
- Dim_Promotion

### Relationships

Dimension tables use one-to-many relationships with the central Fact_Sales table.

## Dashboard Pages

### 1. Executive Overview

Provides a high-level view of:

- Total Sales
- Gross Profit
- Gross Margin
- Total Orders
- Total Customers
- Average Order Value
- Monthly Sales Trends
- Product Category Performance
- Territory Performance

### 2. Product & Category Analysis

Includes:

- Sales by Category
- Sales by Subcategory
- Top 10 Products
- Bottom 10 Products
- Product Sales vs Profitability
- Product Performance Table

### 3. Customer & Geography Analysis

Includes:

- Top Customers
- Customer Sales Distribution
- Sales by Occupation
- Sales by Country
- Sales by Territory Group

### 4. Sales & Promotion Analysis

Includes:

- Monthly Sales Trends
- Sales by Year
- Promotion Performance
- Discount vs Sales Analysis
- Sales vs Profitability

## Key KPIs

| KPI | Result |
|---|---:|
| Total Sales | $22.20M |
| Gross Profit | $9.20M |
| Gross Margin | 41.46% |
| Total Orders | 25,410 |
| Total Customers | 18,220 |
| Average Order Value | $873.76 |
| Sales Lines | 58,154 |

## Data Preparation

The data preparation process included:

- Removing exact duplicate records
- Recovering 5 missing ProductKeys
- Cleaning product and customer tables
- Validating primary and foreign keys
- Validating dates
- Validating numeric fields
- Creating a dedicated Date dimension
- Preparing data for star-schema modeling

## DAX Measures

Key measures include:

- Total Sales
- Total Orders
- Total Customers
- Average Order Value
- Total Cost
- Gross Profit
- Gross Margin %
- Sales YTD
- Sales MTD
- Sales Previous Year
- Sales YoY Growth %
- Product Sales Rank
- Category Sales Rank

## Business Insights

- Bikes represent the dominant share of total sales.
- Road Bikes and Mountain Bikes are the strongest major categories.
- A small number of products contribute a significant portion of revenue.
- North America, Europe, and Pacific are the major territory groups.
- Most sales occurred without a promotion.
- Promotion analysis can help identify relationships between discount levels and sales performance.

## Project Documentation

Detailed documentation is available in the `Documentation` file:

- Business Analysis Report
- Data Cleaning & Transformation Documentation
- Data Model Documentation

## 📊 Dashboard Preview

<table>
<tr>
<td width="50%">

### Executive Overview

<img src="01-Executive Overview.png" width="100%">

</td>
<td width="50%">

### Product & Category

<img src="02-Product & Category Analysis.png" width="100%">

</td>
</tr>

<tr>
<td width="50%">

### Customer & Geography

<img src="03-Customer & Geography Analysis.png" width="100%">

</td>
<td width="50%">

### Sales & Promotion

<img src="04-Sales & Promotion Analysis.png" width="100%">

</td>
</tr>
</table>

## Disclaimer

This repository is intended for portfolio and demonstration purposes. The original source dataset is not included where redistribution is not permitted.

## Author

**Hafiz Rehman**

Data Analyst | Power BI | SQL | Excel | Python

[LinkedIn](https://www.linkedin.com/in/hafiz-rehman-burki)

[GitHub](https://github.com/Hafiz-Rehman123)

[Portfolio](https://hafiz-rehman-data-analyst-portfolio.ai.studio/#home)
