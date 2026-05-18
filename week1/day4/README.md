Day 4 – SQL NULL Handling in Databricks
Overview

This project demonstrates how to handle NULL values in SQL using different SQL functions in Databricks. The notebook includes practical examples using sample datasets for employees, orders, and products.

The main focus of this practice is understanding how SQL handles missing values and how to replace or manage them efficiently using built-in SQL functions.

Tables Used
EmployeesN

Contains employee details such as:

Employee ID
Name
Salary
Bonus
Manager ID
Orders

Contains customer order information:

Order ID
Customer Name
Amount
Discount
Coupon Code
Products

Contains product details:

Product ID
Product Name
Price
Category
Stock
Concepts Covered
1. IS NULL / IS NOT NULL

Used to identify missing or available values.

Examples:
Find employees with NULL salary
Find orders with available discounts
Find products with NULL category
Count employees without managers
2. IFNULL()

Used to replace NULL values with default values.

Examples:
Replace NULL salary with 0
Replace NULL bonus with 1000
Replace NULL order amount with 500
Replace NULL stock with 0
3. COALESCE()

Returns the first non-NULL value from multiple expressions.

Examples:
Use salary, otherwise bonus
Use salary → bonus → 0
Use product price or default value
Use order amount → discount → 0
4. NULLIF()

Returns NULL when two expressions are equal.

Examples:
Convert salary to NULL when salary = 0
Convert discount to NULL when discount = 0
Skills Practiced
SQL NULL handling
Data cleaning concepts
Conditional SQL logic
Databricks SQL execution
Writing optimized SQL queries
Learning Outcome

Through this practice, I learned:

How NULL values behave in SQL
Difference between NULL checking methods
Replacing missing values using IFNULL()
Using COALESCE() for fallback logic
Using NULLIF() for conditional comparisons
Real-world data preprocessing techniques
Technologies Used
SQL
Databricks
Relational Database Concepts
Conclusion

This Day 4 practice strengthened my understanding of NULL handling techniques in SQL. These concepts are essential in Data Engineering, Analytics, and ETL workflows where handling incomplete or missing data is a common requirement.
