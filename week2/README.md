# 🚀 WEEK 2 – DATA ENGINEERING PRACTICE

# 📌 OVERVIEW

This week focused on advanced SQL concepts and real-world data engineering workflows using PySpark and Databricks.

The projects covered:
- Subqueries & CTEs
- End-to-End ETL Pipelines
- Medallion Architecture
- Data Cleaning & Validation
- Delta Tables
- Aggregations & Analytics
- Dashboard-Ready Reporting

The goal of this week was to strengthen practical understanding of SQL and PySpark concepts used in real-world Data Engineering projects.

---

# 🛠️ TECHNOLOGIES USED

- SQL
- PySpark
- Databricks Community Edition
- Delta Lake
- DataFrames
- Window Functions
- Aggregations
- ETL Concepts

---

# 📅 DAY 1 – SQL PRACTICE (SUBQUERIES & CTEs)

# 🎯 OBJECTIVE

Practice advanced SQL concepts using:
- Subqueries
- Common Table Expressions (CTEs)

The focus was on solving real-world analytical problems using nested queries and reusable query structures.

---

# 📂 TABLES USED

## 👨‍💼 Employees Table
Contains:
- Employee ID
- Employee Name
- Department ID
- Salary
- Manager ID

---

## 🏢 Departments Table
Contains:
- Department ID
- Department Name

---

## 🛒 Orders Table
Contains:
- Order ID
- Employee ID
- Order Amount
- Order Date

---

# 📚 CONCEPTS COVERED

## 🔹 SUBQUERIES

### Topics Practiced
- Aggregate subqueries
- Nested filtering
- EXISTS clause
- MIN / MAX subqueries
- Department-based filtering

### Example Problems
- Employees earning above average salary
- Employees with minimum salary
- Employees with orders
- Salary comparisons between departments

---

## 🔹 COMMON TABLE EXPRESSIONS (CTEs)

### Topics Practiced
- WITH clause
- Aggregations inside CTEs
- Joining CTEs with tables
- Salary comparisons
- Department-wise analysis

### Example Problems
- Department average salary
- Employee and department mapping
- Employees earning above department average
- Total order amount per employee

---

# 📊 OUTPUTS GENERATED

- Above-average salary report
- Department salary analysis
- Employee order reports
- Employee-department mapping
- Total order amount calculations

---

# 📖 KEY LEARNINGS

- Difference between Subqueries and CTEs
- Writing cleaner and reusable SQL queries
- Using EXISTS for filtering
- Combining joins with nested logic
- Improving query readability and maintainability

---

# 📅 DAY 2 – END-TO-END ETL PIPELINE USING PYSPARK & DELTA TABLES

# 🎯 OBJECTIVE

Build a complete ETL pipeline using PySpark and Delta Tables.

The project focused on:
- Data ingestion
- Data cleaning
- Type casting
- Derived columns
- Incremental loading
- Delta MERGE operations

---

# 📂 DATASET USED

The dataset contains:
- order_id
- customer_id
- product
- amount
- updated_date

---

# ⚙️ PIPELINE IMPLEMENTATION

## 🔹 NULL HANDLING
- Replaced missing amount values
- Applied fillna()

---

## 🔹 TYPE CASTING
- Converted string columns into numeric types
- Renamed columns for consistency

---

## 🔹 DERIVED COLUMNS
Created:
- bonus column
- category column

Business categories:
- High
- Low

---

## 🔹 USER DEFINED FUNCTIONS (UDFs)

Implemented custom bucket logic:
- Low
- Medium
- High

based on order amount.

---

## 🔹 FULL LOAD

Loaded complete transformed data into:
- target_table

using overwrite mode.

---

## 🔹 INCREMENTAL LOAD

Used Delta Lake MERGE operation for:
- Updating existing records
- Inserting new records

Implemented:
- UPSERT logic

---

# 📊 OUTPUTS GENERATED

- Cleaned dataset
- Derived columns
- Bucketized data
- Full load target table
- Incrementally updated Delta table

---

# 📖 KEY LEARNINGS

- Building ETL pipelines using PySpark
- Handling incremental loads
- Implementing Delta MERGE logic
- Applying business transformations
- Creating scalable data workflows

---

# 📅 DAY 3 – MEDALLION ARCHITECTURE USING PYSPARK

# 🎯 OBJECTIVE

Implement a Medallion Architecture pipeline using PySpark and Delta Lake.

The project focused on:
- Data Cleaning
- Data Validation
- Aggregations
- Customer Analytics
- Dashboard-Ready Reporting

---

# 📂 DATASET USED

The dataset contains:
- order_id
- customer_id
- product
- category
- city
- date
- amount
- quantity

---

# 📚 REQUIREMENTS IMPLEMENTED

## 🔹 SALES ANALYSIS

Generated:
- Product-wise sales
- Category-wise sales
- City-wise sales

---

## 🔹 CUSTOMER INSIGHTS

Generated:
- Number of orders per customer
- Top spending customers

---

## 🔹 DATA QUALITY CHECKS

Implemented:
- NULL handling
- Negative value removal
- Duplicate removal
- Critical column validation

---

## 🔹 LATEST RECORD HANDLING

Used:
- Window Functions
- ROW_NUMBER()

to keep the latest order record.

---

## 🔹 DASHBOARD-READY GOLD TABLES

Created Delta Tables:
- gold_product_sales
- gold_city_sales
- gold_daily_sales
- gold_customer_sales

These tables are ready for reporting tools like:
- Power BI

---

# 🎯 DATA ENGINEERING CONCEPTS PRACTICED

- Medallion Architecture
- Data Cleaning
- Data Validation
- Delta Tables
- Aggregations
- Window Functions
- Customer Analytics
- Reporting Pipelines
- Dashboard Preparation

---

# 📖 KEY LEARNINGS

Through this week, I learned:
- Writing advanced SQL queries using Subqueries and CTEs
- Building end-to-end ETL pipelines
- Handling incremental data loads
- Implementing Delta Lake operations
- Applying Medallion Architecture concepts
- Creating dashboard-ready analytical datasets
- Managing data quality in real-world pipelines

---

# 🚀 REAL-WORLD USE CASES

The concepts implemented this week are widely used in:
- Enterprise Data Warehouses
- Data Lakehouse Architectures
- Financial Reporting Systems
- Customer Analytics Platforms
- Retail & Sales Analytics
- Business Intelligence Dashboards
- Real-Time ETL Pipelines

---

# ✅ CONCLUSION

Week 2 provided strong hands-on experience in advanced SQL and PySpark-based data engineering workflows. The projects helped build practical understanding of ETL pipelines, Medallion Architecture, Delta Lake operations, data validation, and analytical reporting techniques used in real-world enterprise systems.
