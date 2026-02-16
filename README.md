# TASK-3-DATA-ANALYST-
This project demonstrates SQL-based data analysis using a structured Ecommerce database in MySQL. The database includes customers, products, orders, and order_items tables, and various SQL queries were written to extract and analyze meaningful business insights. The task covers core SQL concepts such as SELECT, WHERE, ORDER BY, GROUP BY, aggregate functions (SUM, AVG, COUNT), INNER/LEFT/RIGHT JOINS, subqueries, view creation, index optimization, NULL handling using COALESCE(), and calculation of Average Revenue Per User (ARPU). Through these queries, key insights such as total revenue, average order value, top customers, and revenue by country were identified, demonstrating practical skills in database management and data analysis.

## 📌 Internship: Data Analyst Internship  
## 🛠 Tool Used: MySQL  
## 📂 Database: ecommerce_sql_database  

---

## 🎯 Objective

The objective of this task is to use SQL to extract, manipulate, and analyze structured data from an Ecommerce database.  
This task demonstrates understanding of SQL fundamentals and data analysis techniques.

---

## 🗂 Database Structure

The database consists of the following tables:

1. **customers**
   - customer_id
   - name
   - email
   - country

2. **products**
   - product_id
   - product_name
   - category
   - price

3. **orders**
   - order_id
   - customer_id
   - order_date
   - total_amount

4. **order_items**
   - order_item_id
   - order_id
   - product_id
   - quantity

---

## 📊 SQL Concepts Covered

This task includes:

- ✅ SELECT statements
- ✅ WHERE conditions
- ✅ ORDER BY sorting
- ✅ GROUP BY grouping
- ✅ Aggregate Functions (SUM, AVG, COUNT)
- ✅ INNER JOIN
- ✅ LEFT JOIN
- ✅ RIGHT JOIN
- ✅ Subqueries
- ✅ Views
- ✅ Index optimization
- ✅ NULL handling using COALESCE()
- ✅ Average Revenue Per User (ARPU) calculation

---

## 🔎 Key Analysis Performed

### 1️⃣ Total Revenue
Calculated total revenue using:
```sql
SELECT SUM(total_amount) FROM orders;
