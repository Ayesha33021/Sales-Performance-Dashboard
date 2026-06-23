# Sales-Performance-Dashboard

## Project Overview

This project analyzes retail sales data to uncover trends in customer behavior, product performance, regional sales, and profitability. Using Python, SQL, and Power BI, the project transforms raw sales data into actionable business insights through data analysis and interactive visualizations.

## Objectives

* Analyze retail sales performance across products, customers, and regions.
* Identify top-performing and underperforming products.
* Evaluate the impact of discounts on profitability.
* Discover customer segments contributing most to revenue.
* Build an interactive dashboard for business decision-making.

## Dataset

The project uses the Sample Superstore dataset containing:

* 9,994 sales transactions
* 5,009 unique orders
* Customer, product, and regional information
* Sales, profit, quantity, and discount metrics

## Tools & Technologies

* Python
* Pandas
* NumPy
* SQL
* Power BI
* Excel
* Matplotlib
* Seaborn

## Project Workflow

### 1. Data Cleaning & Preprocessing

* Removed duplicate records
* Converted date columns to datetime format
* Created new features such as:

  * Year
  * Month
  * Quarter
  * Shipping Days
  * Profit Margin

### 2. Exploratory Data Analysis

* Revenue and profit analysis
* Category and product performance evaluation
* Regional sales comparison
* Customer segmentation analysis
* Monthly sales trend analysis

### 3. SQL Analysis

* Aggregated sales and profit metrics
* Analyzed regional and product performance
* Generated customer-level insights

### 4. Power BI Dashboard

Built an interactive dashboard featuring:

* Revenue KPIs
* Profit KPIs
* Customer Insights
* Product Performance Analysis
* Geographic Sales Analysis
* Trend Analysis

## Key Insights

### Sales Performance

* Total Revenue: $2.30M
* Total Profit: $286K
* Total Orders: 5,009

### Top Category

* Technology generated the highest revenue ($836K).

### Best Performing Region

* West region generated the highest sales ($725K).

### Customer Insights

* Consumer segment contributed the largest share of revenue.

### Discount Impact

* Discounts above 20% significantly reduced profitability.
* Products with high discounts frequently generated losses.

### Regional Profitability

* California and New York were the most profitable states.
* Texas generated the highest overall loss.


## Repository Structure

```text
Sales-Performance-Dashboard/
│
├── data/
│   ├── SampleSuperstore.csv
│   └── superstore_cleaned.csv
│
├── notebooks/
│   └── sales_analysis.ipynb
│
├── sql/
│   └── sales_queries.sql
│
├── dashboard/
│   └── SalesDashboard.pbix
│
├── screenshots/
│
└── README.md
```




