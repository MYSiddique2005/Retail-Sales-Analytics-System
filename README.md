# Retail Sales Analytics System — Python, SQL

## Project Overview

Built a retail sales analytics system using Python and SQL to analyze 9,994 retail transactions containing customer orders, product categories, regional sales, discounts, and profit data.

Performed data preprocessing, feature engineering, exploratory data analysis (EDA), and SQL-based business analysis to identify sales trends, profitable categories, high-value customers, and loss-making products.

---

## Dataset Details

- Total Records: 9,994
- Total Orders: 5,009
- Total Sales: 2.29M+
- Total Profit: 286K+
- Regions Analyzed: 4
- Product Categories: 3
- Customer Segments: 3

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLite
- Jupyter Notebook
- Git & GitHub

---

## Data Preprocessing

Performed:
- datetime conversion for order and shipping dates
- duplicate record validation
- missing value analysis
- statistical analysis of numerical columns

Created new business features:
- Order Year
- Order Month
- Shipping Days
- Profit Margin %

---

## Exploratory Data Analysis (EDA)

### Sales Trend Analysis
- Analyzed monthly sales trends across 12 months
- Identified November as highest revenue month with 352K+ sales
- Identified February as lowest sales month

### Regional Analysis
- West region generated highest sales: 725K+
- South region showed lowest sales performance

### Category Analysis
- Technology category generated highest sales: 836K+
- Furniture category showed very low profitability despite high sales

### Product Analysis
- Identified top 10 products by sales
- Canon imageCLASS 2200 Advanced Copier generated 61K+ sales

### Customer Analysis
- Analyzed top-performing customers
- Highest customer sales exceeded 25K+

### Segment Analysis
- Consumer segment generated 1.16M+ sales
- Corporate segment generated 706K+ sales

### Loss Analysis
- Detected 1,871 loss-making transactions
- Identified products generating losses up to 8.8K

---

## SQL Business Analysis

Performed SQL analysis using SQLite database.

Implemented:
- KPI queries
- sales aggregation
- customer ranking
- profitability analysis
- regional sales analysis
- shipping performance analysis
- monthly sales analysis

SQL concepts used:
- SUM()
- AVG()
- COUNT()
- DISTINCT
- GROUP BY
- ORDER BY
- LIMIT
- CAST()

---

## Key Business Insights

- Technology was the most profitable category with 145K+ profit
- Furniture generated only 18K profit despite high sales
- November and December showed strongest seasonal sales performance
- Standard Class shipping averaged 5 days delivery time
- Multiple products generated significant financial losses
- Consumer segment contributed highest overall revenue

---

## Project Structure

Retail-Sales-Analytics-System/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
├── reports/
├── sql/
├── visuals/
├── src/
│
├── README.md
├── requirements.txt
├── retail_sales.db
└── main.py
