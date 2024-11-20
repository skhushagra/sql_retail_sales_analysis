
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
## 📝 Findings
**Customer Demographics**:
Customers span various age groups, with significant purchases in categories such as Clothing and Beauty.

**High-Value Transactions**:
Multiple transactions exceeded $1000, suggesting premium purchases.

**Sales Trends**:
Monthly analysis highlights variations in sales and helps identify peak seasons.

**Customer Insights**:
Top customers and popular product categories were identified, offering actionable insights for business decisions.


## 🚀 Conclusion
This project provided hands-on experience with SQL, showcasing the power of structured queries for data exploration, cleaning, and analysis. By analyzing retail sales data, we derived actionable business insights, identified trends, and understood customer behaviors, offering a comprehensive foundation for future SQL projects.
