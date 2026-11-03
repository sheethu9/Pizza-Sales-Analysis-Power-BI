# Pizza-Sales-Analysis-Power-BI
# 🍕 Pizza Sales Analysis Using SQL

## 📌 Project Overview
This project focuses on analyzing pizza sales data using **MySQL** to identify key business insights, sales trends, customer ordering patterns, and best- and worst-performing pizzas.

The analysis helps understand overall business performance and supports data-driven decision-making.

## 🎯 Project Objectives
- Calculate key performance indicators (KPIs).
- Analyze daily and monthly order trends.
- Understand sales distribution by pizza category and size.
- Identify the top 5 and bottom 5 pizzas based on revenue, quantity sold, and total orders.
- Analyze sales performance using SQL queries and filters.

## 🛠️ Tools & Technologies
- **Database:** MySQL
- **SQL Concepts:** SELECT, SUM, COUNT, DISTINCT, GROUP BY, ORDER BY, WHERE, LIMIT, ROUND, CAST, Subqueries, Date Functions.
- **Tool:** MySQL Workbench

## 📊 Key Performance Indicators (KPIs)

The following KPIs were calculated:

1. **Total Revenue:** Total revenue generated from pizza sales.
2. **Average Order Value:** Average revenue generated per order.
3. **Total Pizzas Sold:** Total number of pizzas sold.
4. **Total Orders:** Total number of unique orders.
5. **Average Pizzas Per Order:** Average number of pizzas purchased per order.

## 📈 Business Analysis

### 1. Daily Trend for Total Orders
Analyzed the number of orders placed on each day of the week to identify daily ordering patterns.

### 2. Monthly Trend for Orders
Analyzed monthly order volumes to understand sales patterns throughout the year.

### 3. Percentage of Sales by Pizza Category
Calculated the percentage contribution of each pizza category to total revenue.

### 4. Percentage of Sales by Pizza Size
Analyzed the revenue contribution of different pizza sizes.

### 5. Total Pizzas Sold by Category
Identified the total quantity of pizzas sold under each category.

### 6. Top 5 Pizzas by Revenue
Identified the five pizzas generating the highest revenue.

### 7. Bottom 5 Pizzas by Revenue
Identified the five pizzas generating the lowest revenue.

### 8. Top 5 Pizzas by Quantity
Identified the five most-selling pizzas based on quantity.

### 9. Bottom 5 Pizzas by Quantity
Identified the five least-selling pizzas based on quantity.

### 10. Top 5 Pizzas by Total Orders
Identified the five pizzas appearing in the highest number of unique orders.

### 11. Bottom 5 Pizzas by Total Orders
Identified the five pizzas appearing in the lowest number of unique orders.

## 🔍 Additional Analysis
Used SQL WHERE clauses to filter data based on:
- Pizza Category (Classic, Supreme, Veggie, Chicken).
- Pizza Size (S, M, L, XL, XXL).
- Specific months using the MONTH() function.

These filters help perform more detailed and focused sales analysis.

## 💡 SQL Skills Demonstrated
- Data aggregation using SUM() and COUNT().
- Grouping data using GROUP BY.
- Sorting results using ORDER BY.
- Filtering records using WHERE.
- Removing duplicates using DISTINCT.
- Limiting results using LIMIT.
- Formatting numerical results using ROUND() and CAST().
- Working with date functions.
- Writing subqueries for percentage calculations.

## 📂 Project Structure

```text
Pizza-Sales-Analysis/
│
├── README.md
├── Pizza Sales SQL Queries.sql
└── Dataset/
    └── pizza_sales.csv
```

## 📌 Conclusion
This project demonstrates how SQL can be used to analyze real-world sales data and extract meaningful business insights.

By analyzing revenue, order trends, pizza categories, sizes, and product performance, this project provides a better understanding of pizza sales and business performance.

---

**Project Type:** Data Analysis | SQL Project  
**Author:** Sheethal K
