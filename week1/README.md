# 🚀 DATA ENGINEERING PRACTICE – WEEKLY README

# 📌 OVERVIEW

This repository contains my complete hands-on practice work in SQL, PySpark, Databricks, Data Cleaning, Data Validation, Transformations, Window Functions, Analytics, and ETL Pipelines.

Throughout this week, I worked on multiple real-world datasets and implemented different data engineering concepts using:
- SQL
- PySpark
- Databricks Community Edition

The projects focus on:
- Data Cleaning
- Data Validation
- SQL Analytics
- Window Functions
- Customer Segmentation
- Aggregations
- ETL Pipelines
- Reporting & Business Insights

---

# 🛠️ TECHNOLOGIES USED

- SQL
- PySpark
- Databricks Community Edition
- DataFrames
- Window Functions
- ETL Concepts
- Aggregations
- Regex
- Data Cleaning Techniques

---

# 📅 DAY 1 – ADVANCED ANALYTICS & REPORTING (PYSPARK / SQL)

## 🎯 OBJECTIVE

Perform advanced analytics on datasets using:
- Window Functions
- Aggregations
- Customer Segmentation
- Final Reporting Tables

---

## 📂 DATASETS USED

- customers
- orders
- order_items
- products

---

## ⚙️ TASKS PERFORMED

- Loaded datasets into PySpark DataFrames
- Handled null values
- Converted data types
- Joined datasets using:
  - customer_id
  - order_id

Applied:
- Window Functions
- Aggregations
- Running Totals
- Customer Segmentation

Created:
- Final Reporting Dataset

---

## 📚 CONCEPTS COVERED

### 🔹 WINDOW FUNCTIONS

Used for ranking and analytical calculations.

#### Functions Practiced
- RANK()
- DENSE_RANK()
- SUM() OVER()

#### Use Cases
- Top customers per city
- Running sales totals
- Product rankings

---

### 🔹 AGGREGATIONS

#### Functions Used
- SUM()
- COUNT()

#### Business Metrics Generated
- Total Sales
- Total Orders
- Customer Lifetime Value (CLV)

---

### 🔹 CUSTOMER SEGMENTATION

#### Segments
- Gold → High spenders
- Silver → Medium spenders
- Bronze → Low spenders

---

## 📊 OUTPUTS GENERATED

- Top 3 Customers per City
- Daily Sales with Running Totals
- Top Products
- Customer Lifetime Value
- Customer Segmentation
- Final Reporting Table

---

## 📖 KEY LEARNINGS

- Real-world usage of window functions
- Difference between aggregation and window functions
- Importance of data validation
- Building reporting pipelines

---

# 📅 DAY 2 – SQL PRACTICE (GROUP BY & JOINS)

## 🎯 OBJECTIVE

Practice SQL aggregation and table joining concepts.

---

## 📚 TOPICS COVERED

### 🔹 GROUP BY

#### Concepts Practiced
- SUM()
- COUNT()
- AVG()
- MAX()
- MIN()
- HAVING Clause

#### Use Cases
- Department-wise salary analysis
- Sales reporting
- Product revenue analysis

---

### 🔹 JOINS

#### Types of JOINS Practiced
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL JOIN
- SELF JOIN

#### Use Cases
- Employee and department mapping
- Customer and sales analysis
- Missing record identification
- Multi-table reporting

---

## 📖 KEY LEARNINGS

- GROUP BY with aggregate functions
- Difference between WHERE and HAVING
- Combining data from multiple tables
- Understanding relationships using joins

---

# 📅 DAY 3 – WINDOW FUNCTIONS, CASE WHEN & REGEX

## 🎯 OBJECTIVE

Strengthen SQL skills using:
- Window Functions
- CASE WHEN
- Regular Expressions

---

## 📚 TOPICS COVERED

### 🔹 WINDOW FUNCTIONS

#### Functions Practiced
- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- SUM() OVER()
- COUNT() OVER()

#### Concepts Used
- PARTITION BY
- ORDER BY

---

### 🔹 CASE WHEN

Used conditional logic similar to if-else statements.

#### Use Cases
- Salary categorization
- Dynamic column generation
- Conditional transformations

---

### 🔹 REGEX

#### Concepts Practiced
- Pattern matching
- Extracting usernames from emails
- Extracting numbers from strings
- Character classes
- Quantifiers

---

## 📖 KEY LEARNINGS

- Window functions do not reduce rows like GROUP BY
- CASE WHEN improves query readability
- Regex is useful for data cleaning and parsing
- Combining these concepts enables advanced analytics

---

# 📅 DAY 4 – SQL NULL HANDLING IN DATABRICKS

## 🎯 OBJECTIVE

Learn how to handle NULL values using SQL functions inside Databricks.

---

## 📂 TABLES USED

- EmployeesN
- Orders
- Products

---

## 📚 CONCEPTS COVERED

### 🔹 BASIC NULL OPERATIONS

#### Topics Practiced
- IS NULL
- IS NOT NULL
- Counting NULL values

---

### 🔹 IFNULL()

Used to replace NULL values with defaults.

#### Examples
- Replace NULL salary with 0
- Replace NULL bonus with 1000
- Replace NULL stock with 0

---

### 🔹 COALESCE()

Returns the first non-NULL value.

#### Examples
- salary → bonus → 0
- amount → discount → 0

---

### 🔹 NULLIF()

Returns NULL when values match.

#### Examples
- Convert salary to NULL if salary = 0
- Convert discount to NULL if discount = 0

---

## 📖 KEY LEARNINGS

- Understanding NULL behavior in SQL
- Replacing missing values
- Applying fallback logic
- Real-world preprocessing techniques

---

# 📅 DAY 5 – PYSPARK TRANSFORMATIONS & TYPE CASTING

## 🎯 OBJECTIVE

Explore PySpark transformations and type casting using Databricks Community Edition.

---

## 📚 TOPICS COVERED

### Concepts Practiced
- Reading CSV files
- Creating DataFrames
- withColumn()
- Column transformations
- Type casting
- Dropping columns
- Data cleaning

---

## 📖 KEY LEARNINGS

- Working with PySpark DataFrames
- Data transformation techniques
- Type conversion handling
- Preparing datasets for analytics

---

# 🚗 CAR SALES DATA PIPELINE (PYSPARK + SQL)

## 🎯 OBJECTIVE

Build a complete end-to-end data pipeline using PySpark and SQL.

---

## 📂 DATASETS USED

- customers
- cars
- sales
- dealers
- sales_dealer

---

## ⚙️ PIPELINE STAGES

### 🔹 PHASE 1 – DATA UNDERSTANDING

#### Tasks Performed
- Loaded datasets
- Inspected schema
- Performed profiling

#### Issues Identified
- Null values
- Negative prices
- Invalid foreign keys
- Inconsistent formatting

---

### 🔹 PHASE 2 – DATA CLEANING

#### Techniques Used
- fillna()
- String trimming
- Removing invalid records
- Standardization

---

### 🔹 PHASE 3 – DATA VALIDATION

#### Validation Techniques
- Anti Joins
- Foreign key checks

#### Validations Performed
- Invalid customers
- Invalid cars
- Rejected records tracking

---

### 🔹 PHASE 4 – DATA TRANSFORMATION

#### Metrics Generated
- Revenue per Customer
- Cars Sold per Brand
- City-wise Revenue
- Total Customer Spend

---

### 🔹 PHASE 5 – SQL ANALYSIS

#### Business Insights Generated
- Top Customers
- Repeat Customers
- Monthly Sales Trends
- City-wise Analytics

---

### 🔹 PHASE 6 – OUTPUT

Final processed datasets were generated and saved successfully.

---

# 🎯 DATA ENGINEERING SKILLS PRACTICED

- ETL Pipeline Development
- Data Cleaning
- Data Validation
- Data Transformation
- SQL Analytics
- Window Functions
- Customer Segmentation
- Reporting & Business Insights
- Handling Real-World Data Issues

---

# 📖 OVERALL LEARNINGS

Through this week of practice, I learned:
- Building end-to-end data pipelines
- Writing advanced SQL queries
- Using PySpark for large-scale transformations
- Handling NULL values and invalid data
- Applying window functions in analytics
- Performing customer segmentation
- Generating business insights from raw data
- Importance of validation and clean data pipelines

---

# ✅ CONCLUSION

This week provided strong hands-on experience in SQL, PySpark, Databricks, analytics, and ETL workflows. The projects helped me understand how real-world data engineering pipelines are designed, cleaned, transformed, validated, and analyzed to generate business insights and reporting datasets.
