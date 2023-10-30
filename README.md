# HomeSales_DH
Overview of Requirements:

This review invloves using SparkSQL to determine key metrics about home sales data. This isncludes creating temporary views, partition the data, caching/uncaching a temporary table, and verify that the table has been uncached.


The compalatiom of the data using SparkSQL is to be used to answer the following questions:

1. What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

2. What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

3. What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

4. What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.


5. After caching the data "home_sales", and running a query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

6. Partition by the "date_built" field on the formatted parquet home sales data.

7. Create a temporary table for the parquet data.

8. Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

9. Uncache the home_sales temporary table.

10. Verify that the home_sales temporary table is uncached using PySpark.

11. Download your Home_Sales.ipynb file and upload it into your "Home_Sales" GitHub repository.

