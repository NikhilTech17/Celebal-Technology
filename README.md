# Celebal-Technology

# celebal-week1-assignment
CEI-Celebal Technologies Week 1 Assignment - Data exploration and cleaning using Python Pandas and Jupyter Notebook.

# Celebal Technologies - Week 1 Assignment
# Objective
Learn Python basics and perform basic data exploration and cleaning using Pandas.

# Tasks Performed
Loaded the CSV dataset using Pandas

# Explored dataset using:

head()
tail()
shape
columns
info()
Checked missing values

Removed unnecessary columns

Removed duplicate rows

Cleaned currency symbols from final_price column

Converted columns into numeric data types

Created quantity and total_amount columns

Filtered products based on ratings

Saved the cleaned dataset as cleaned_dataset.csv

# Technologies Used
Python
Pandas
Jupyter Notebook
Files Included
assignment.ipynb → Complete notebook with code and outputs
cleaned_dataset.csv → Cleaned dataset
README.md → Project documentation
Dataset Source
Original dataset was taken from Kaggle Shopping Dataset.

# Output
A cleaned and processed dataset ready for basic data analysis.

# Learning Outcome
Through this assignment, I learned:

Basic Python programming
Data exploration using Pandas
Data cleaning techniques
Handling missing values
Removing duplicates
Creating derived columns
Saving cleaned datasets
Using Jupyter Notebook and GitHub

# celebal-week2-assignment
CEI-Celebal Technologies Week 2 Assignment - SQL sales data analysis using SQLite with filtering, aggregation, and business insights.

# SQL Sales Data Analysis - Week 2 Assignment
# Objective
Analyze sales data using SQL with filtering, aggregation, sorting, and business-oriented queries.

# Tasks Performed
Loaded the sales dataset into SQLite database

# Explored the dataset using:

Table schema
Sample records
Row count validation
Applied filtering using WHERE clause:

# Region-wise filtering
Category-wise filtering
Date-based filtering
Sales-based filtering
Performed aggregations using GROUP BY:

# Total sales by region
Total quantity by category
Average sales by category
Sorted and limited results:

# Top products by sales
Top categories by sales
Solved business use cases:

# Monthly sales trends
Top customers by revenue
Duplicate record detection
Performed data validation:

# Record count verification
Sales range checks
Missing value checks
Technologies Used
SQL
SQLite
DB Browser for SQLite
GitHub
# Files Included
sql_script.sql → Complete SQL queries
query_results.pdf  → Query outputs
README.md → Project documentation
# Output
Successfully analyzed the sales dataset using SQL and generated meaningful business insights through filtering, aggregation, and trend analysis.

# Brief Insights
Sales performance varies across different regions and categories.
A few products contribute significantly to overall sales.
Monthly trend analysis helps identify business growth patterns.
Top customers generate a large share of revenue.
Data quality checks confirmed the dataset is suitable for analysis.
Learning Outcome
Through this assignment, I learned:

SQL query writing
Data exploration using SQL
Filtering data with WHERE clause
Aggregation using GROUP BY functions
Sorting and limiting query results
Solving business problems using SQL
Data validation and quality checks
Managing SQL projects using GitHub


# celebal-week3-assignment
CEI-Celebal Technologies Week 3 Assignment - SQL Sales Analysis with Superstore Dataset using Subqueries, CTEs, Window Functions, and SQLite.

# Superstore Sales Analysis using SQL (SQLite)
This project analyzes the Superstore dataset using SQL concepts such as:

# Subqueries
Common Table Expressions (CTEs)
Window Functions (RANK, ROW_NUMBER)
Joins
Customer Sales Analysis
Business Insights
# Objectives
Analyze customer sales performance
Identify top and bottom customers
Find above-average sales customers
Rank customers based on total sales
Generate business insights from sales data
# Tools Used
SQLite
DB Browser for SQLite
SQL
Dataset
# Superstore Sales Dataset link: https://www.kaggle.com/datasets/vivek468/superstore-dataset


# celebal-week4-assignment
# Azure Cloud Fundamentals and Data Pipeline Implementation using Azure Data Factory
# Objective
To understand Azure cloud concepts and build an end-to-end data pipeline using Azure Storage Account and Azure Data Factory (ADF).

# Project Overview
This project demonstrates the creation of a complete data integration workflow in Microsoft Azure. A CSV dataset was uploaded to Azure Blob Storage and processed through Azure Data Factory. The pipeline validates file metadata and copies the data from a source container to a destination container.

# Services Used
Azure Resource Group
Azure Storage Account
Azure Blob Storage
Azure Data Factory (ADF)
Azure IAM (Reader and Contributor Roles)

# Implementation Steps
Created a Resource Group in Azure.
Created a Storage Account and Blob Containers.
Uploaded the CSV dataset to the source container.
Created Azure Data Factory and explored Author, Monitor, and Manage modules.
Configured a Linked Service to connect ADF with Azure Blob Storage.
Created Source and Destination Datasets.
Used the Get Metadata activity to retrieve file details.
Built a pipeline using the Copy Data activity.
Executed the pipeline using Debug/Trigger.
Monitored pipeline execution in ADF Monitor.
Assigned IAM roles (Reader and Contributor) to ensure secure access.
Validated metadata and successfully copied the file to the destination container.
Pipeline Flow
Source Blob Storage ↓ Get Metadata ↓ Copy Data Activity ↓ Destination Blob Storage

# Results
Successfully connected Azure Data Factory to Azure Blob Storage.
Retrieved file metadata including file name, size, and last modified date.
Successfully copied the dataset from the source container to the destination container.
Verified pipeline execution through ADF Monitor.
Implemented secure access using Azure IAM roles.

# Conclusion
This project provided hands-on experience with Azure cloud services and Azure Data Factory. An end-to-end data pipeline was successfully implemented, demonstrating data movement, metadata validation, monitoring, and access management within the Azure ecosystem.
