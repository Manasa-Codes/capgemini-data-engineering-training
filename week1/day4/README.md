🚀 DAY 4 – SQL NULL HANDLING IN DATABRICKS
📌 OVERVIEW

This project demonstrates how to handle NULL values in SQL using different SQL functions inside Databricks.

The notebook contains practical examples using sample datasets related to:

Employees
Orders
Products

The main goal of this practice is to understand how SQL manages missing values and how to replace or process them efficiently using built-in SQL functions.

🛠️ TABLES USED
👨‍💼 EmployeesN

This table stores employee information such as:

Employee ID
Employee Name
Salary
Bonus
Manager ID
🛒 Orders

This table contains customer order details:

Order ID
Customer Name
Order Amount
Discount
Coupon Code
📦 Products

This table stores product-related data:

Product ID
Product Name
Price
Category
Stock
📚 CONCEPTS COVERED
🔹 LEVEL 1 – BASIC NULL OPERATIONS
✅ Topics Practiced
IS NULL
IS NOT NULL
Counting NULL values
✅ Operations Performed
Display employees with NULL salary
Display orders with available discounts
Display products where category is NULL
Count employees without manager IDs
🔹 LEVEL 2 – IFNULL()
✅ Purpose

IFNULL() is used to replace NULL values with default values.

✅ Operations Performed
Replace NULL salary with 0
Replace NULL bonus with 1000
Replace NULL order amount with 500
Replace NULL stock with 0
🔹 LEVEL 3 – COALESCE()
✅ Purpose

COALESCE() returns the first non-NULL value from multiple expressions.

✅ Operations Performed
Use salary, otherwise bonus
Use salary → bonus → 0
Use product price or default value
Use order amount → discount → 0
🔹 LEVEL 4 – NULLIF()
✅ Purpose

NULLIF() returns NULL when two expressions are equal.

✅ Operations Performed
Convert salary to NULL when salary = 0
Convert discount to NULL when discount = 0
🎯 SKILLS PRACTICED
SQL NULL Handling
Data Cleaning Techniques
Conditional SQL Functions
Databricks SQL
Query Writing and Testing
📖 LEARNING OUTCOMES

Through this practice, I learned:

How NULL values behave in SQL
Difference between IS NULL and IS NOT NULL
Using IFNULL() to replace missing values
Using COALESCE() for fallback logic
Using NULLIF() for conditional comparisons
Real-world data preprocessing techniques
💻 TECHNOLOGIES USED
SQL
Databricks
Relational Database Concepts
✅ CONCLUSION

This Day 4 practice helped strengthen my understanding of SQL NULL handling techniques. These concepts are very important in real-world Data Engineering and Analytics projects because handling missing or incomplete data is a common requirement in production systems.
