#  Phase 2 – SQL to PySpark Transformations & Data Analysis

##  Objective

This phase focuses on applying SQL concepts in PySpark by solving analytical problems using joins, aggregations, and filtering. It helps in understanding how SQL queries translate into PySpark transformations.


## Problem Statement (Summary)

• Perform aggregations like total spend and average values
• Identify top customers based on spending
• Join multiple datasets (customers and orders/sales)
• Filter data based on conditions
• Identify customers with no orders
• Sort and rank data based on business metrics

Detailed problem statement is available in:
phase2_problem_statement.pdf

##  Dataset Used

• Dataset: Sample datasets from Spark Playground
• Source: Spark Playground tutorials
• Tables used: customers, sales (orders equivalent)

##  Approach

1. Loaded datasets into PySpark DataFrames
2. Cleaned data by handling null values
3. Performed aggregations using `groupBy()` and aggregation functions
4. Applied joins to combine customer and sales data
5. Used filtering and sorting for analysis
6. Converted SQL queries into equivalent PySpark transformations


## Key Transformations

• `groupBy()` with `sum()`, `avg()`, `count()`
• `join()` (inner join, left join)
• `filter()` for conditions
• `orderBy()` for sorting
• `limit()` for top results

## Output / Results

• Total spend per customer
• Top customers based on revenue
• Customers with no orders
• Average order value per customer
• Sorted customer spending data

(Optional: Add screenshots in /outputs folder)



##  Challenges Faced

• Understanding join conditions correctly
• Handling column ambiguity after joins
• Deciding when joins are required vs direct aggregation
• Converting SQL logic into PySpark syntax


##  Learnings

• Mapping SQL operations to PySpark transformations
• Importance of joins in data analysis
• Efficient use of aggregation functions
• Writing analytical queries in both SQL and PySpark


## Files in this Folder

• phase2_problem_statement.pdf → Problem description
• solution.py / notebook → Implementation
• outputs/ → Results 