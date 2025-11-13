Customer Behavior Analysis – End-to-End Data Analytics Project


#Overview
This project presents a complete data analytics pipeline focused on understanding customer purchasing behavior.
It covers Python-based data loading & cleaning, Exploratory Data Analysis (EDA), SQL-based business insights, and an interactive Power BI dashboard.
The objective is to identify spending patterns, customer segments, discount impact, shipping preferences, and product performance.

#Dataset
The dataset (loaded in Python and used across SQL & Power BI) includes customer-level purchase information with fields such as:
Customer demographics: gender, age group
Purchase details: item purchased, category, purchase amount
Behavioral data: previous purchases, subscription status
Operational fields: shipping type, discount applied, review rating
Dataset Source: Provided CSV (loaded and cleaned in Python notebook)
Rows: (add count from your notebook)
Columns: (add number)

Tools & Technologies
Python – Pandas, NumPy, Matplotlib/Seaborn
MySQL – SQL queries for customer insights
Power BI – Data visualisation dashboard
Jupyter Notebook – Python analysis (customer_analysis_py.ipynb)
GitHub – Version control

#Steps Performed
1. Data Loading (Python)
Loaded dataset using Pandas.
Inspected structure, missing values, and summary statistics.
Converted data types and standardized column names.

2. Data Cleaning
Handled missing values and incorrect entries.
Removed duplicates.
Cleaned categorical columns (Yes/No, gender, shipping type).
Prepared a final cleaned dataset for SQL and Power BI.

3. Exploratory Data Analysis (EDA)
Distribution of purchase amounts
Gender-wise spending patterns
Discount vs. non-discount revenue
Category and product performance
Correlation checks and trend analysis
Identified potential KPIs for dashboard

4. SQL Insights (MySQL)
The customer_analysis.sql file contains key business-focused queries, including:

Revenue by gender
Customers using discounts but spending above average
Top 5 highest-rated products
Purchase comparison: Standard vs Express shipping
Subscriber vs non-subscriber spending
Top items with highest discount dependency
Customer segmentation (New / Returning / Loyal)
Top 3 products per category
Repeat buyers and subscription likelihood
Revenue by age group
These queries help identify spending behavior, loyalty patterns, and product trends.

5. Power BI Dashboard
The interactive dashboard (customer_analysis_dashboard.pbix) includes:
Total revenue & average purchase KPIs
Gender-wise revenue comparison
Discount usage analysis
Top products by rating and orders
Customer segments & demographics
Category-wise performance visuals
Subscriber vs non-subscriber insights
The dashboard enables quick insights through slicers and drill-downs.

