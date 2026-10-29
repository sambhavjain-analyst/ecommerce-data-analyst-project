# Ecommerce Sales Analysis Project

## 1. Project Overview

This project analyzes e-commerce sales data to understand sales performance, profitability, customer behavior, product performance, and order trends. Python, Pandas, MySQL, and Power BI were used to clean, analyze, query, and visualize the data.

## 2. Project Objectives

- Analyze total sales, profit, and profit margin.
- Identify the most profitable product categories and products.
- Understand monthly sales trends.
- Analyze payment methods, shipping modes, and customer types.
- Evaluate product returns and discount impact.
- Build an interactive Power BI dashboard for business decision-making.

## 3. Tools and Technologies

- **Python:** Data cleaning and exploratory data analysis.
- **Pandas:** Data manipulation and analysis.
- **Jupyter Notebook:** Executing Python analysis.
- **MySQL:** Database storage and SQL queries.
- **Power BI Desktop:** Interactive dashboard and visualizations.
- **CSV:** Dataset storage and data transfer.

## 4. Dataset Description

The cleaned dataset contains 10,000 rows and 26 columns. It includes information related to orders, sales, profit, products, categories, customers, payment methods, shipping modes, discounts, marketing channels, and returns.

## 5. Data Cleaning

Data cleaning was performed using Python and Pandas.

- Checked and handled missing values.
- Filled missing ratings using the median rating.
- Replaced missing marketing channel values with "Unknown".
- Removed 20 duplicate records.
- Converted the order date column to datetime format.
- Created Year and Month columns for time-based analysis.
- Exported the cleaned dataset to a CSV file.

## 6. Exploratory Data Analysis

Exploratory data analysis was conducted to identify patterns in sales and profitability.

The analysis covered:
- Overall sales and profit.
- Category-wise performance.
- Monthly sales and profit trends.
- Payment methods and shipping modes.
- New and returning customers.
- Product returns.
- Marketing channel performance.
- Customer demographics.
- Discount levels and profitability.
- Relationships between numerical variables.

## 7. SQL Analysis

The cleaned data was imported into the MySQL database `ecommerce_analysis`, in the `sales` table.

SQL analysis included:
- Aggregate functions for total sales, profit, and orders.
- Category-wise sales and profit analysis.
- Top products ranked by sales and profit.
- Common Table Expressions (CTEs).
- Window functions such as RANK() and LAG().
- CASE statements for profit margin classification.
- Month-over-month sales growth.
- Customer revenue and repeat-customer analysis.

## 8. Power BI Dashboard

An interactive Power BI dashboard was developed to visualize key performance indicators and business trends.

The dashboard includes:
- Total Sales.
- Total Profit.
- Profit Margin.
- Total Orders.
- Monthly Sales Trend.
- Sales and Profit by Category.
- Orders by Payment Method.
- Orders by Shipping Mode.
- Orders by Customer Type.
- Orders by Return Status.
- Top 10 Products by Profit.

Interactive slicers allow users to filter the dashboard by Category, Customer Type, and City.

## 9. Key Business Insights

1. **Overall sales:** Approximately ₹15.99 crore.
2. **Overall profit:** Approximately ₹2.70 crore.
3. **Profit margin:** Approximately 16.87%.
4. **Total orders:** 10,000.
5. **Category performance:** Electronics generated the highest total profit, approximately ₹1.64 crore.
6. **Profit margin:** Sports had the highest category-level profit margin, approximately 18.30%.
7. **Sales trend:** July recorded the highest monthly sales, while November recorded the lowest.
8. **Payment preference:** UPI was the most frequently used payment method, with 3,931 orders.
9. **Returns:** 878 orders were marked as returned, representing an 8.78% return rate.
10. **Discount impact:** Orders with a 30% discount had a negative total profit of approximately ₹1.4 lakh.

## 10. Business Recommendations

- Focus on maintaining Electronics performance while exploring growth opportunities in other categories.
- Study successful Sports category margins to identify practices that could improve profitability elsewhere.
- Investigate the November sales decline and develop targeted promotional campaigns.
- Review high-discount orders to prevent discounts from reducing profitability.
- Analyze returned orders to identify product, quality, or delivery issues.
- Continue evaluating UPI adoption and customer purchasing behavior.
- Use the interactive dashboard to monitor KPIs and support regular business reviews.

## 11. Conclusion

This project demonstrates an end-to-end data analysis workflow, from data cleaning and exploratory analysis to SQL-based investigation and interactive dashboard development. The findings provide insights into revenue, profitability, customer behavior, returns, and discount effectiveness.

The project also demonstrates practical skills in Python, Pandas, MySQL, SQL analytics, and Power BI.

## 12. Project Files

The project is organized into the following folders and files:

- **Raw Dataset:** `data/ecommerce_sales_raw.csv`
- **Cleaned Dataset:** `data/ecommerce_sales_cleaned.csv`
- **Python Data Cleaning Notebook:** `notebooks/01_Data_Cleaning.ipynb`
- **SQL Analysis File:** `data/e commerce sql.sql`
- **Power BI Dashboard:** `dashboard/ECOMMERCE SALES & PROFIT ANALYTICS.pbix`
- **Final Project Report:** `report/Ecommerce_Sales_Analysis_Report.md`

These files contain the datasets, data cleaning workflow, SQL queries, interactive dashboard, and project documentation.