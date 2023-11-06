# Home_Sales Challenge
In this challenge, you will leverage your knowledge of SparkSQL to derive essential metrics from home sales data. You will utilize Spark to establish temporary views, partition data, cache and uncache a temporary table, and validate the uncaching of the table.

Instructions:

1. Rename the "Home_Sales_starter_code.ipynb" file to "Home_Sales.ipynb".
2. Import the required PySpark SQL functions for this task.
3. Read the data from the "home_sales_revised.csv" file in the starter code into a Spark DataFrame.
4. Create a temporary table named "home_sales".

Answer the following questions using SparkSQL:

1. Determine the average price for a four-bedroom house sold in each year, rounding your answer to two decimal places.

2. Find the average price of a home for each year it was built, with three bedrooms and three bathrooms, rounding to two decimal places.

3. Calculate the average price of a home for each year with three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet, rounding your answer to two decimal places.

4. Identify the "view" rating for homes priced at or above $350,000. Determine the query runtime, rounding it to two decimal places.

5. Cache your temporary table "home_sales".

6. Check if your temporary table is cached.

Using the cached data:
1. Execute the query that filters out view ratings with an average price greater than or equal to $350,000. Calculate the runtime and compare it to the uncached runtime.

2. Partition the formatted Parquet home sales data by the "date_built" field.
3. Create a temporary table for the Parquet data.

Using the Parquet data:
1. Run the query that filters out view ratings with an average price greater than or equal to $350,000. Determine the runtime and compare it to the uncached runtime.

2. Uncache the temporary table "home_sales".

3. Verify that the "home_sales" temporary table is uncached using PySpark.

4. Download your "Home_Sales.ipynb" file and upload it to your "Home_Sales" GitHub repository. 

## How to Install and Run the code

To run this script:
1. Copy the git link and clone it to your local git repository
2. Ensure *Home_Sales_colab.ipynb* file is present
3. Run the file either using google colab by uploading the notebook from your local folder or follow the next step
4. Run the script using **Jupyter Notebook** and view results
5. Be sure to run the entire script using *Restart & Run All option* from *Kernel* in *Jupyter Notebook* to get error free results
6. Or, you could alternatively run each block of code individually starting from the very top 

## Credits

To work on this challenge, I worked with my project partner and peer from the class.

## Resources

https://colab.research.google.com/?utm_source=scs-index


