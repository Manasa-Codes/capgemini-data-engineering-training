# 🚀 SQL PRACTICE – SUBQUERIES & CTEs

# 📌 OVERVIEW

This project focuses on practicing advanced SQL concepts using:
- Subqueries
- Common Table Expressions (CTEs)

The notebook contains multiple real-world SQL scenarios using employee, department, and order datasets. The practice helped in understanding how nested queries and CTEs simplify complex SQL operations and improve query readability.

---

# 🛠️ TECHNOLOGIES USED

- SQL
- Databricks
- Relational Database Concepts

---

# 📂 TABLES USED

## 👨‍💼 Em (Employees)

This table stores employee information:
- Employee ID
- Employee Name
- Department ID
- Salary
- Manager ID

---

## 🏢 Dep (Departments)

This table stores department details:
- Department ID
- Department Name

---

## 🛒 Ord (Orders)

This table stores order details:
- Order ID
- Employee ID
- Order Amount
- Order Date

---

# 📚 CONCEPTS COVERED

# 🔹 SUBQUERIES

## 📖 Definition

A subquery is a query written inside another SQL query. It is used to perform intermediate calculations or filtering.

---

## ✅ SUBQUERY QUESTIONS PRACTICED

### 1️⃣ Find employees who earn more than average salary

### 2️⃣ Find employees who belong to the same department as 'Alice'

### 3️⃣ Get employees whose salary is equal to the minimum salary

### 4️⃣ Find employees who have placed at least one order

### 5️⃣ Get employees whose salary is greater than employees in department 102

---

## 🎯 SUBQUERY SKILLS PRACTICED

- Aggregate subqueries
- Nested filtering
- EXISTS clause
- MIN / MAX subqueries
- Department-based filtering

---

# 🔹 COMMON TABLE EXPRESSIONS (CTEs)

## 📖 Definition

A Common Table Expression (CTE) is a temporary result set that improves readability and simplifies complex SQL queries.

CTEs are created using the `WITH` clause.

---

## ✅ CTE QUESTIONS PRACTICED

### 1️⃣ Create a CTE to show employees with salary greater than 50,000

### 2️⃣ Find average salary per department using CTE

### 3️⃣ Use CTE to get employees and their department names

### 4️⃣ Find total order amount per employee using CTE

### 5️⃣ Find employees whose salary is above department average using CTE

---

## 🎯 CTE SKILLS PRACTICED

- Using WITH clause
- Aggregations inside CTEs
- Joining CTEs with tables
- Department-wise analysis
- Salary comparisons
- Reusable query structures

---

# 📊 OUTPUTS GENERATED

The following outputs were generated:
- Employees with above-average salary
- Employees in same department
- Employees with minimum salary
- Employees with orders
- Department average salary report
- Employee and department mapping
- Total order amount per employee
- Employees earning above department average

---

# 📖 KEY LEARNINGS

Through this practice, I learned:
- How subqueries work in SQL
- Difference between subqueries and CTEs
- Using EXISTS for conditional filtering
- Writing cleaner queries using CTEs
- Combining joins, aggregations, and nested logic
- Improving SQL query readability and maintainability

---

# 🎯 USE CASES

These SQL concepts are widely used in:
- Data Analysis
- Business Reporting
- Employee Analytics
- Financial Reporting
- ETL Pipelines
- Advanced SQL Querying

---

# ✅ CONCLUSION

This practice session strengthened my understanding of Subqueries and Common Table Expressions (CTEs) in SQL. These concepts are essential for writing advanced SQL queries and solving real-world analytical problems efficiently.

Source file: :contentReference[oaicite:0]{index=0}
