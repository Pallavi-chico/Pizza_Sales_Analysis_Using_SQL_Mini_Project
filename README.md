# Pizza Sales Analysis Using SQL

This project explores a pizza store's sales data using structured SQL queries. By connecting four interrelated tables, the project answers 13 business-relevant questions ranging from revenue calculation to order trends and category performance. It demonstrates strong skills in data exploration, joins, aggregation, subqueries, and window functions.

# Dataset
The project uses the `pizza_db` database, consisting of four key tables:

- `orders`: Contains order timestamps and order IDs.
- `order_details`: Contains quantity of each pizza in an order.
- `pizzas`: Contains pizza sizes and prices.
- `pizza_types`: Contains names and categories of pizza types.

# Questions Answered

1. **Total number of orders placed**
2. **Total revenue generated from pizza sales**
3. **Highest-priced pizza**
4. **Most common pizza size ordered**
5. **Top 5 most ordered pizza types by quantity**
6. **Total quantity ordered by each pizza category**
7. **Distribution of orders by hour**
8. **Category-wise distribution of pizzas**
9. **Average number of pizzas ordered per day**
10. **Top 3 pizza types by revenue**
11. **Percentage contribution of each pizza category to revenue**
12. **Cumulative revenue over time**
13. **Top 3 pizza types by revenue per category**

# Skills Demonstrated

- SQL Joins (`INNER JOIN`)
- Aggregate functions (`SUM`, `COUNT`, `AVG`)
- Grouping and Sorting (`GROUP BY`, `ORDER BY`)
- Subqueries and CTEs
- Window Functions (`RANK()`, `OVER`)
- Data Cleaning & Transformation (e.g., rounding revenue)

# File Structure

- `pizza_sales_analysis.sql`: Main SQL script answering all 13 questions
- `README.md`: Project overview and documentation

# How to Use

1. Load the `pizza_db` database in your SQL environment (MySQL/PostgreSQL).
2. Run the queries in `pizza_sales_analysis.sql` sequentially.
3. Analyze the output to draw business insights.

# Sample Insight

> The **top 3 revenue-generating pizzas** are:  
> 1. The **Classic Deluxe**  
> 2. The **BBQ Chicken**  
> 3. The **Mediterranean Veggie**
