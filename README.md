
# Retail Sales Analysis

## 📋 Project Overview

**Project Title:** Retail Sales Analysis  
**Skill Level:** Beginner  
**Database:** `sql_project`  

This project aims to demonstrate SQL skills and techniques used in data analysis by exploring, cleaning, and analyzing retail sales data. It involves creating a retail sales database, performing exploratory data analysis (EDA), and answering key business questions through SQL queries. This project is ideal for those starting their journey in data analysis and looking to build a strong foundation in SQL.

---

## 🎯 Objectives

1. **Database Setup:** Create and populate a retail sales database.
2. **Data Cleaning:** Identify and remove records with missing or null values.
3. **Exploratory Data Analysis (EDA):** Gain a better understanding of the dataset.
4. **Business Analysis:** Use SQL to answer specific business questions and derive actionable insights.

---

## 🗂️ Project Structure

### 1. Database Setup

#### **Database Creation**  
The project starts by creating a database named `p1_retail_db`.  

#### **Table Creation**  
A table named `retail_sales` is created with the following structure:  
```sql
CREATE TABLE retail_sales
(
    transactions_id INT PRIMARY KEY,
    sale_date DATE,
    sale_time TIME,
    customer_id INT,
    gender VARCHAR(10),
    age INT,
    category VARCHAR(35),
    quantity INT,
    price_per_unit FLOAT,
    cogs FLOAT,
    total_sale FLOAT
);
---

## 📝 Findings

### 1. Customer Demographics  
- The dataset includes customers from various age groups.  
- Sales are distributed across diverse categories, with significant activity in **Clothing** and **Beauty**.  

### 2. High-Value Transactions  
- Several transactions had a total sale amount exceeding **1000**, indicating premium purchases.  

### 3. Sales Trends  
- Monthly analysis reveals fluctuations in sales, helping identify **peak seasons** and periods of lower activity.  

### 4. Customer Insights  
- The analysis highlights **top-spending customers** and the **most popular product categories**, offering actionable insights for targeted strategies.

---

## 📊 Reports

### 1. Sales Summary  
- A comprehensive overview of total sales, customer demographics, and category performance.

### 2. Trend Analysis  
- Detailed insights into sales trends across months and shifts (Morning, Afternoon, Evening).  

### 3. Customer Insights  
- Reports identifying top customers based on total sales.  
- Counts of unique customers for each category, offering a better understanding of category-specific customer engagement.

---

## 🚀 Conclusion

This project serves as a **comprehensive introduction to SQL for data analysts**, covering:  
- **Database setup:** Creating and managing a structured database.  
- **Data cleaning:** Ensuring data integrity by removing null or incomplete records.  
- **Exploratory data analysis (EDA):** Gaining valuable insights into data structure and patterns.  
- **Business-driven SQL queries:** Answering key business questions through analytical SQL techniques.

### Key Outcomes:  
- The findings from this project help drive **data-informed business decisions** by understanding sales patterns, customer behavior, and product performance.  
- It establishes a foundation for deeper data analysis and advanced SQL projects.

---

This project provided hands-on experience with SQL, showcasing the power of structured queries for data exploration, cleaning, and analysis. By analyzing retail sales data, we derived actionable business insights, identified trends, and understood customer behaviors, offering a comprehensive foundation for future SQL projects.
