# Home_Sales

## Overview
This project uses PySpark and SparkSQL to analyze home sales data by calculating metrics, creating temporary views, partitioning data, and optimizing performance with caching.

### Features
- Calculate average home prices based on various criteria (e.g., bedrooms, bathrooms, size, view ratings).

- Optimize query performance through caching and partitioning.

- Use PySpark for scalable data processing and SQL queries.

### Usage
1. Load the home_sales_revised.csv file into a Spark DataFrame.

2. Create a temporary table and execute SQL queries to:
    - Calculate average prices based on bedrooms, bathrooms, and size.
    - Compare cached vs. uncached query performance.
    - Partition data by date_built and query the results.

3. Export results as needed.

### Requirements
- Python 3.7+
- PySpark library
- home_sales_revised.csv dataset