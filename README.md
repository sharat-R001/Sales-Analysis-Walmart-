Walmart Sales Analysis — SQL + Python Project
Overview
This project performs end-to-end analysis on Walmart sales data to identify sales trends, branch performance, customer behavior, and profitability. It combines Python and SQL to create a structured, reproducible, and scalable analytics workflow for retail data.

Project Goals
Analyze sales trends by branch, product category, and time.

Identify high- and low-performing branches.

Understand customer behavior patterns and peak transaction times.

Examine payment method preferences.

Assess product line profitability.

Tech Stack
Python (via Anaconda and Jupyter Notebook)

MySQL (local or hosted server)

Libraries:

pandas

sqlalchemy

mysql-connector-python

Data Preparation
Load raw Walmart sales CSV into Pandas.

Perform basic EDA:

Check for missing values, nulls, incorrect types, duplicates.

Clean and format data:

Fix column types

Handle nulls

Convert currency strings to numeric

Standardize column names

Feature Engineering
Create new column:
Total_Amount = Unit Price × Quantity

Ensure column names and data types are SQL-compliant.

MySQL Integration
Establish connection using sqlalchemy and mysql-connector-python.

Create database and tables.

Upload cleaned dataset from Pandas to MySQL.

SQL Analysis
Use SQL queries to answer business questions:

Sales trends over time and across branches

Revenue by product category and branch

Payment method distribution

Ratings and customer feedback patterns

Peak sales hours and days

Profit margins by product line

Key Findings
Fashion and Food & Beverages are top-selling categories.

Branch C consistently reports the highest revenue.

E-wallets show increasing popularity among customers.

Transactions and customer ratings peak on weekends, especially between 12:00–15:00.

Requirements
Anaconda + Jupyter Notebook

MySQL Server

Python libraries:

pandas

sqlalchemy

mysql-connector-python

Dataset
Walmart Sales Data
Source: Kaggle (public dataset)
