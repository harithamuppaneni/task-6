# task-6
TASK 6 - Sales Trend Analysis Using Aggregations

## Objective
Analyze monthly revenue and order volume from the online_sales dataset using SQL aggregate functions.

## Tools Used
- MySQL Workbench

## Steps Performed
- Created a table online_sales with sample order data.
- Inserted test data including order dates, amounts, and product IDs.
- Used SQL functions:
  - YEAR() and MONTH() to extract time info.
  - SUM() to calculate monthly revenue.
  - COUNT(DISTINCT product_id) to count monthly orders.
- Grouped and ordered results for clear trend analysis.

## Output
The query displays the revenue and number of orders for each month (see screenshot).

## Files Included
- sales_trend_analysis.sql: SQL code file
- results_screenshot.png: Output of SQL query result
