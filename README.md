# Walmart Sales Analysis — SQL + Python Project

## Overview

This project performs end-to-end analysis on Walmart sales data to identify sales trends, branch performance, customer behavior, and profitability. It combines Python and SQL to create a structured, reproducible analytics workflow for retail data.

## Project Goals

- Analyze sales trends by branch, product category, and time.
- Identify high- and low-performing branches.
- Understand customer behavior patterns and peak transaction times.
- Examine payment method preferences.
- Assess product line profitability.

## Tech Stack

- **Python** (via Anaconda and Jupyter Notebook)
- **MySQL** (local or hosted server)

### Python Libraries

- pandas  
- sqlalchemy  
- mysql-connector-python  

## Data Preparation

- Load raw Walmart sales CSV into Pandas.
- Perform basic EDA:
  - Check for missing values
  - Inspect data types
  - Remove duplicates
- Clean and format data:
  - Fix column types
  - Handle null values
  - Convert currency strings to numeric values
  - Standardize column names for SQL compatibility

## Feature Engineering

- Add new derived column:
  - `Total_Amount = Unit Price × Quantity`
- Ensure consistent column names and data types for database ingestion.

## MySQL Integration

- Connect using `sqlalchemy` and `mysql-connector-python`
- Create schema and tables via Python
- Upload cleaned dataset from Pandas DataFrame to MySQL

## SQL Analysis

Use SQL queries to answer core business questions:

- Sales trends by date, branch, and category
- Revenue distribution across product lines
- Popularity of payment methods
- Peak transaction periods by hour and day
- Customer ratings and feedback analysis
- Profitability metrics by branch and category

## Key Findings

- **Top Categories**: Fashion and Food & Beverages consistently drive high sales.
- **Branch Comparison**: Branch C outperforms others in revenue.
- **Payment Preference**: E-wallet usage is rapidly increasing.
- **Customer Behavior**: Transactions and ratings peak during weekends, especially between 12:00 PM and 3:00 PM.

## Dataset

- Walmart Sales Data  
- Source: [Kaggle - Walmart Sales Data](https://www.kaggle.com/datasets)

## License

This project is for educational and analytical purposes only. It is not affiliated with or endorsed by Walmart Inc.
