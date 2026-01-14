# E-commerce Sales Dashboard (Power BI)

## Project Overview
This project analyzes e-commerce sales data using Power BI to uncover sales trends, best-selling products, and high-revenue markets. The dashboard is designed to support data-driven business decisions.

## Objectives
- Analyze total sales performance over time
- Identify top-selling products by revenue
- Compare sales performance across countries
- Provide high-level KPIs for quick insights

## Tools Used
- Power BI Desktop
- Power Query (data cleaning and transformation)
- DAX (measures and calculated columns)
- GitHub (version control and documentation)

## Dataset
The dataset contains transaction-level e-commerce sales data with the following fields:
- InvoiceID
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

Note: Negative quantities represent discounts or returns and were retained for accurate sales calculations.

## Key Features of the Dashboard
- Monthly sales trend analysis (January–December)
- Top 10 products by total sales
- Total sales by country
- KPI cards for Total Sales and Total Quantity

## Dashboard Preview
See the `screenshots/` folder for dashboard visuals.

## Project Structure

Ecommerce-Sales-Dashboard/
├── data/
│ ├── raw/
│ └── processed/
├── powerbi/
│ └── Ecommerce_Sales_Dashboard.pbix
├── screenshots/
├── documentation/
└── README.md

## Insights Summary
- Sales show clear monthly patterns, indicating seasonality.
- A small number of products contribute a large share of total revenue.
- Sales performance varies significantly across countries with major sales made in the United Kingdom.

## Author
Isaiah Okech