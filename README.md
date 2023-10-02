# Home_Sales


In this task, you will apply your understanding of SparkSQL to extract important metrics from home sales data. Your workflow will involve using Spark to create temporary views, partition the data, cache and uncache a temporary table, and confirm that the table has been successfully uncached.


**Instructions**

1.  Import the necessary PySpark SQL functions for this assignment.
2.  Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.
3.  Create a temporary table called home_sales.
4.  Answer the following questions using SparkSQL:

    1. A Spark DataFrame is created from the dataset.

    2. A temporary table of the original DataFrame is created.

    3. A query is written that returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year. 

    4. A query is written that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms. 

    5. A query is written that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 
       2,000 square feet for each year built rounded to two decimal places. 

    6. A query is written that returns the view rating for the average price for homes that are greater than or equal to $350,000, rounded to two 
       decimal places. (The output shows the run time for this query.) 

    7. A cache of the temporary "home_sales" table is created and validated. 

    8. The query from step 6 is run on the cached temporary table, and the run time is computed.

    9. A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read. 

    10. A temporary table of the parquet data is created. 

    11. The query from step 6 is run on the parquet temporary table, and the run time is computed. 

    12. The "home_sales" temporary table is uncached and verified. 
