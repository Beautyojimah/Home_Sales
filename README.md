# Home Sales Analysis with PySpark

This project utilizes PySpark to perform an analysis on home sales data. The dataset contains various details about home sales, including the number of bedrooms, bathrooms, square footage, view rating, date built, year sold, water front and price.

## Objectives

1. **Data Loading and Pre-processing:**
   - Load the home sales data into a Spark DataFrame.
   - Create a temporary table for querying.

2. **Data Analysis:**
   - Calculate the average price for a four-bedroom house sold each year.
   - Determine the average price of a home for each year it was built, focusing on homes with three bedrooms and three bathrooms.
   - Find the average price of a home for each year, considering homes that have three bedrooms, three bathrooms, two floors, and are greater than or equal to 2,000 square feet.
   - Analyze the "view" rating for homes costing more than or equal to $350,000.

3. **Performance Optimization:**
   - Cache and uncache the temporary table and observe the effect on query runtime.
   - Partition the data by the "date_built" field and save it in parquet format. Compare the runtime of queries on the partitioned data to the original data.



## Files

- `Home_Sales.ipynb`: Jupyter notebook containing the PySpark code for data analysis and performance optimization.
- `home_sales_revised.csv`: The home sales dataset from s3 bucket.


## Prerequisites

- Python
- PySpark
- Jupyter Notebook

