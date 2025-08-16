# Retail Sales Analysis 🛒  

This project is a **SQL-based analysis** of retail sales data. It demonstrates SQL skills typically used by data analysts to explore, clean, and analyze business data.  

The project involves setting up a retail sales database, performing exploratory data analysis (EDA), and answering specific business questions using SQL queries.  

---

## 🔹 Project Overview  
- **Database**: `sales_data`  
- **Table**: `order_detials` (stores sales transactions)  
- **Goal**: Explore, clean, and analyze retail sales data to uncover customer behavior, product performance, and sales trends.  

---

## 🔹 Objectives  
1. **Database Setup**: Create and populate the retail sales database.  
2. **Data Cleaning**: Identify and remove missing or null records.  
3. **EDA (Exploratory Data Analysis)**: Perform basic data exploration.  
4. **Business Analysis**: Answer key business questions using SQL queries.  

---

## 🔹 Database & Table Creation  

```sql
CREATE DATABASE sales_data;

CREATE TABLE order_detials (
    transactions_id INT,
    sale_date DATE,
    sale_time TIME,
    customer_id INT,
    gender VARCHAR(10),
    age INT,
    category VARCHAR(15),
    quantiy INT,

---

## 🔹 Key Business Queries  

Below are some of the important business questions answered using SQL in this project:  

1. **What were the total sales and revenue generated?**  
   ```sql
   SELECT SUM(total_sale) AS total_sales, SUM(cogs) AS total_cogs 
   FROM order_detials;
---

## 🔹 Findings  
- Customers are spread across multiple age groups with sales across categories like **Clothing** and **Beauty**.  
- Several **high-value transactions (>1000)** were identified.  
- **Monthly sales trends** show seasonal variations and peak months.  
- **Top 5 customers** contribute significantly to total sales.  
- Unique customer counts vary by category, showing **diverse shopping behavior**.  

---

## 🔹 Reports Generated  
- **Sales Summary** → Total sales, customers, product performance.  
- **Trend Analysis** → Monthly & shift-based sales patterns.  
- **Customer Insights** → Top customers & demographics.  

---

## 🔹 Tools Used  
- **SQL (MySQL)** → Queries, Joins, Aggregations, Window Functions  
- **Excel / CSV** → Dataset storage & initial exploration  

---

## 🔹 Conclusion  
This project highlights how SQL can be used to perform data cleaning, exploratory analysis, and generate business insights from retail sales data.  

It serves as a strong foundation for **Data Analyst roles**, showcasing skills in querying, reporting, and deriving insights from real-world datasets.  

---


