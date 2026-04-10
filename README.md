## Data Analysis Project - Customer and Sales Insights

# Project Overview
This project analyzes customer purchase behavior and sales data using Python.  
The goal is to understand customer segments, revenue patterns, and time-based trends.

# Dataset
- File: data.csv
- Contains:
  - CustomerID
  - Quantity
  - UnitPrice
  - InvoiceDate
  - Country

# Steps Performed

1. Data Cleaning
- Removed missing values
- Checked data types
- Prepared data for analysis

2. Feature Engineering
- Created TotalPrice = Quantity * UnitPrice
- Extracted Month from InvoiceDate

3. Data Analysis
- Customer segmentation using quantiles
- Outlier analysis
- Top customers analysis
- Country revenue analysis
- Time-based revenue analysis

# Key Insights

1. VIP Customers
A small group of customers contributes most of the revenue.

2. Country Distribution
Revenue is mostly concentrated in a few countries.

3. Customer Segments
Customers fall into different spending groups.

4. Outliers
Some customers spend much more than average.

5. Time Trends
Sales change over time and are not constant.

Tools Used
- Python
- Pandas
- Matplotlib

# Conclusion
This project shows that customer behavior can be grouped and analyzed to understand sales patterns and improve business decisions.