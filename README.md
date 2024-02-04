# AtliQ-Hardware-Insights-using-SQL

### Learnings:

✨ Learned Subqueries, CTEs, Views, Temporary Tables: Explored advanced techniques to write complex queries using Subqueries, making queries more readable and maintanable using Common Table Expressions (CTEs), and created and utilized Views and Temporary tables for efficient data handling.

✨ Fundamentals of ETL, Data Warehouse, OLAP, OLTP: Gained a comprehensive understanding of Extract, Transform, Load (ETL) processes, data warehousing concepts, and the difference between Online Analytical Processing (OLAP) and Online Transactional Processing (OLTP).

✨ User Defined Functions, Stored Procedures: Learned to create and use User-defined functions and Stored procedures to enhance SQL code reusability and optimize performance.

✨Window Functions: Explored advanced analytical functions like OVER, ROW_NUMBER, RANK, DENSE_RANK, etc., enabling me to perform complex calculations and analysis within result sets.

✨ Real Dataset with >1 million records: Engaged in industry-style project-based learning using a large-scale dataset, allowing me to apply the acquired skills in a real-world context and develop a solid foundation for working with substantial data volumes.

Here are the all the tasks to be completed:
✅ For Finance Analysis:-

1) Generate a yearly report for Croma India where there are two columns:

   1) Fiscal Year
   2) Total Gross Sales amount In that year from Croma.

2) Generate monthly gross sales report for any customer using stored procedure.

3) Write a stored procedure that can retrieve market badge. i.e. if total sold quantity > 5 million that market is considered "Gold" else "Silver".

The Queries are provided in the text file.

✅ For Top Products, Customers and Markets:-

1) Get top 5 market by net sales in fiscal year 2021.
2) Write Stored procedure to get top n markets by net sales for a given year.
3) Write Stored procedure that takes market, fiscal_year and top n as an input and returns top n customers by net sales in that given fiscal year and market.
4) Write a stored procedure to get the top n products by net sales for a given year.
5) Use product name without a variant. Input of stored procedure is fiscal_year and top_n parameter.
6) Find customer wise net sales distibution per region for FY 2021.
7) Find out top 3 products from each division by total quantity sold in a given year, and, Creating stored procedure for the above query.
8) Retrieve the top 2 markets in every region by their gross sales amount in FY=2021.

✅ For Supply Chain Analysis:-

1) Forecast accuracy report using cte.
2) Forecast accuracy report using temporary table.
3) Write a query for the below scenario.

The supply chain business manager wants to see which customers’ forecast accuracy has dropped from 2020 to 2021. Provide a complete report with these columns: customer_code, customer_name, market, forecast_accuracy_2020, forecast_accuracy_2021.
