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
    price_per_unit FLOAT,
    cogs FLOAT,
    total_sale FLOAT
);
