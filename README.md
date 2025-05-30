🛒 Walmart Sales Analysis — SQL + Python Project
An end-to-end data analytics project to extract actionable business insights from Walmart sales data using Python (Jupyter) and MySQL. This project focuses on building a clean data pipeline, solving key business questions with SQL, and presenting a scalable analysis workflow for retail datasets.

🚀 Project Overview
Goal: Identify sales patterns, branch performance, customer behavior, and profitability metrics.

Tech Stack:

Python (Anaconda, Jupyter Notebook) for data cleaning and transformation

MySQL for advanced business logic and querying

Pandas, SQLAlchemy, MySQL-Connector for integration and scripting

📁 Project Structure
plaintext
Copy
Edit
├── data/              # Raw and processed datasets
├── notebooks/         # Jupyter notebooks for data processing
├── sql_queries/       # Business SQL queries
├── main.py            # Core data pipeline (optional script version)
├── requirements.txt   # List of Python dependencies
└── README.md          # Project documentation
🛠️ Key Steps
Environment Setup

Use Anaconda and Jupyter Notebook for a modular and visual development environment.

Ensure MySQL is installed and accessible via connector libraries.

Data Loading & Preparation

Load Walmart data using Pandas.

Perform EDA: check schema, nulls, types, and outliers.

Clean data: remove duplicates, fix types, handle missing values, format currency.

Feature Engineering

Create Total_Amount column (unit_price × quantity).

Standardize column names and formats for SQL compatibility.

Load into MySQL

Use SQLAlchemy and mysql-connector-python to push clean data into a MySQL database.

Automate table creation and data upload from Python.

SQL Analysis

Write and run SQL queries to address key business questions:

Sales trends by branch, category, and time

Best and worst-performing branches

Payment method preferences

Customer behavior and peak transaction times

Profitability by product line

📊 Business Insights
Top Categories: Fashion and Food & Beverages consistently lead sales volume.

Branch Comparison: Branch C shows highest revenue; Branch B lags.

Payment Trends: E-wallets show fastest growth in customer preference.

Customer Behavior: Ratings and sales peak on weekends between 12–3 PM.

📝 Requirements
Anaconda + Jupyter Notebook

MySQL Server (local or hosted)

Python Libraries:

pandas

sqlalchemy

mysql-connector-python


🙌 Acknowledgments
Dataset: Walmart Sales Data (via Kaggle)

Inspired by real-world business reporting needs in retail analytics

