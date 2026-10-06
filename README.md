# SQL Sales Analytics

## Project Overview

This project uses SQL to analyze sales, customer, and product data and generate business-focused insights.

The analysis covers overall business performance, customer behaviour, product performance, sales trends, customer segmentation, and product segmentation.

## Objectives

The project answers key business questions such as:

- What are the overall sales and order metrics?
- Which countries and customer segments contribute the most?
- Which product categories generate the highest revenue?
- Which products are the top and bottom performers?
- Who are the highest-value customers?
- How do sales change over time?
- What percentage of overall sales comes from each product subcategory?
- How can customers be segmented based on spending and relationship duration?
- How can products be segmented based on revenue performance?

## Database Tables

The analysis uses three main tables:

- `fact_sales` — sales transactions
- `customers` — customer information
- `dim_products` — product and category information

## SQL Techniques Used

The project demonstrates:

- SELECT and filtering
- Aggregate functions
- GROUP BY and ORDER BY
- JOINs
- Subqueries
- CTEs
- CASE statements
- UNION ALL
- Window functions
- `RANK()` / `DENSE_RANK()`
- `LAG()`
- Running totals
- Moving averages
- Date functions
- `DATETRUNC()`
- `DATEDIFF()`
- `GETDATE()`
- Percentage calculations
- Views

## Analysis Areas

### Business KPIs

Calculated:

- Total Sales
- Total Quantity Sold
- Average Selling Price
- Total Orders
- Total Products
- Total Customers

### Customer Analysis

Analyzed:

- Customers by country
- Customers by gender
- Customer revenue
- Top 10 customers by revenue
- Customers with the fewest orders
- Customer spending behaviour
- Customer lifespan

### Product Analysis

Analyzed:

- Products by category
- Average product cost by category
- Revenue by category
- Top 5 products by revenue
- Bottom 5 products by revenue
- Product cost ranges
- Product performance segments

### Time-Based Analysis

Performed:

- Yearly sales analysis
- Monthly sales analysis
- Running total of sales
- Moving average of selling price
- Year-over-year product sales comparison
- Previous-year sales comparison

### Customer Segmentation

Customers were classified into:

- **VIP** — at least 12 months of history and spending of 5,000 or more
- **Regular** — at least 12 months of history and spending below 5,000
- **New** — less than 12 months of history

### Product Segmentation

Products were classified based on total sales into:

- High Performer
- Mid-range
- Low Performer

## SQL Views

Two analytical views were created:

### `report_customer`

A customer-level analytical report containing:

- Customer details
- Age and age segment
- Customer segment
- Recency
- Total orders
- Total sales
- Total quantity
- Total products purchased
- Average order value
- Average monthly spend

### `report_product`

A product-level analytical report containing:

- Product details
- Category and subcategory
- Cost
- Recency
- Product performance segment
- Total orders
- Total sales
- Total quantity sold
- Average selling price
- Average monthly revenue

## Tools

- SQL Server
- SQL

## Repository Contents

- `Project 2.sql` — SQL queries used for the complete analysis.

## Disclaimer

This project is created for learning and portfolio purposes. The data does not contain confidential or personally identifiable information.
