## Home Sales - PySpark SQL Challenge 
## Overview
This project uses PySpark SQL to analyze a large dataset of home sales. The challenge focuses on extracting meaningful metrics, optimizing query performance using caching and partitioning, and validating data transformations. This assignment is part of Module 22 in the Data Science curriculum.

## Objective
Leverage PySpark to:

Analyze home sales data from a CSV file.

Perform SQL queries on a Spark DataFrame using temporary views.

Improve performance with caching and partitioning techniques.

Measure and compare query runtimes with and without optimization.

## Technologies Used
Python 3.5

PySpark (Spark SQL)

Jupyter Notebook

## Data
The dataset used is:

home_sales_revised.csv – Available via AWS S3.

It includes information on:

Home prices

Bedrooms, bathrooms, floors

Year built

View rating

Square footage

## Key Tasks
✅ Data Preparation
Read CSV file into a Spark DataFrame.

Create a temporary view named home_sales.

## 🔍 Data Analysis with Spark SQL
Answer the following:

Average price for four-bedroom houses sold per year.

Average price of homes (3 bed / 3 bath) per year built.

Average price for 3 bed / 3 bath / 2 floor homes ≥ 2000 sq ft, per year built.

Average price per "view" rating where average price ≥ $350,000 (with runtime recorded).

## 🚀 Performance Optimization
Cache the home_sales table and rerun the last query to compare performance.

Partition the dataset by date_built into Parquet format and re-query.

Compare runtimes between cached, uncached, and partitioned versions.

## 🧹 Cleanup
Uncache the home_sales temporary table.

Verify uncache operation using PySpark.
