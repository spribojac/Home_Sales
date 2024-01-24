# Home_Sales
Module 22 Big Data

# Home Sales Data Analysis
## Introduction
This project analyzes home sales data using PySpark, focusing on various queries to gain insights into the real estate market. The dataset used is home_sales_revised.csv.

## Instructions
1. **File Renaming:**
The notebook file has been renamed to Home_Sales.ipynb.

2. **Setup:**
Ensure you have PySpark installed and configured in your environment.

3. **Data Loading:**
The home_sales_revised.csv data is loaded into a Spark DataFrame, and a temporary table named home_sales is created.

4. **Queries Using SparkSQL:**
The following queries are answered using SparkSQL:
Average price for a four-bedroom house sold each year.
Average price of a home for each year it was built with three bedrooms and three bathrooms.
Average price of a home for each year with three bedrooms, three bathrooms, two floors, and area greater than or equal to 2,000 square feet.
"View" rating for homes costing more than or equal to $350,000, with runtime analysis.

5. **Caching:**
The home_sales temporary table is cached, and caching status is verified.

7. **Filtering Cached Data:**
A query filters out view ratings with an average price greater than or equal to $350,000 using both cached and uncached data, with runtime comparisons.

7. **Parquet Data and Partitioning:**
The formatted parquet home sales data is partitioned by the "date_built" field, and a temporary table is created.

9. **Query on Parquet Data:**
A query filters out view ratings with an average price greater than or equal to $350,000 using the parquet data, with runtime comparisons.

9.**Uncaching:**
The home_sales temporary table is uncached, and uncaching status is verified.

11. **Notebook Upload:**
The Home_Sales.ipynb file is uploaded to the "Home_Sales" GitHub repository.

## Dependencies
PySpark

## Usage
1. Open the Home_Sales.ipynb notebook in a PySpark environment.
2. Run each cell sequentially to execute the data analysis and queries.
