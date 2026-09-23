 E-Commerce Customer & Sales Analytics

📌 Project Overview

An end-to-end data analytics project built to analyze e-commerce transaction data and generate actionable business insights.

The project covers data cleaning, exploratory data analysis, customer segmentation, SQL analytics, product and return analysis, and an interactive Power BI dashboard.

 🎯 Business Problem

E-commerce businesses generate large amounts of transactional data, but raw data alone does not provide clear insights into:

- Sales performance
- Customer purchasing behavior
- High-value customer segments
- Product performance
- Product returns
- Customer retention

This project transforms raw transaction data into meaningful analytics to support data-driven business decisions.

🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- SQLite
- SQL
- Power BI
- DAX
- Jupyter Notebook
- Git & GitHub

SQL Concepts Used

- SELECT & WHERE
- GROUP BY & HAVING
- CASE WHEN
- CTEs
- RANK()
- DENSE_RANK()
- LAG()
- Window Functions
- Aggregations

🧹 Data Cleaning & EDA

The transaction dataset was prepared using Python and Pandas.

Key steps included:

- Handling missing values
- Removing duplicate records
- Converting data types
- Creating date-based features
- Identifying invalid quantities and prices
- Identifying returned transactions
- Creating revenue-related features
- Analyzing sales trends
- Analyzing products and countries

 👥 Customer Analytics

Customer behavior was analyzed using **RFM (Recency, Frequency, Monetary) analysis**.

Customers were segmented into groups such as:

- Champions
- Loyal Customers
- Potential Loyalists
- New Customers
- At Risk
- Lost Customers

Additional customer analytics included:

- Customer Lifetime Value (CLV)
- Repeat vs One-Time Customers
- Pareto / 80-20 Analysis
- Cohort Analysis
- Customer Retention


📊 SQL Analysis

SQL was used to perform business-oriented analysis on the cleaned transaction data.

Examples include:

- Top customers by revenue
- Top-selling products
- Country-wise sales
- Monthly revenue analysis
- Customer segmentation analysis
- Revenue growth analysis
- Ranking customers and products


 📈 Power BI Dashboard

The final analysis was converted into an interactive Power BI dashboard.

 Dashboard Pages

1. Executive Overview

Provides an overall view of:

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Monthly Revenue Trend
- Revenue by Product
- Revenue by Country

 2. Customer & RFM Analysis

Provides insights into:

- Customer Segmentation
- Revenue by Customer Segment
- Customer RFM Metrics
- Customer Revenue
- Purchase Frequency

3. Product & Returns Analysis

Provides insights into:

- Average Return Rate
- Total Units Returned
- Total Units Sold
- Top Products by Return Rate
- Top Products by Quantity Sold
- Top Products by Revenue

💡 Key Business Insights

The project helps answer important business questions such as:

- Which customers generate the most revenue?
- Which customer segments are most valuable?
- Which products generate the highest revenue?
- Which products have higher return rates?
- Which countries contribute the most sales?
- How does revenue change over time?
- How many customers are repeat purchasers?
- Which customers may require retention strategies?


📁 Project Structure

Ecommerce_Customer_Sales_Analytics
│
├── data
│   ├── raw
│   └── cleaned
│
├── python
│   ├── 01_Data_Loading_Inspection.ipynb
│   ├── 02_Statistics_Feature_Engineering.ipynb
│   ├── 03_SQL_Analysis.ipynb
│   └── 04_Advanced_Customer_Analytics.ipynb
│
├── sql
│   └── ecommerce_analytics.db
│
├── powerbi
│   └── Customer_Sales_Dashboard.pbix
│
├── reports
│
└── README.md

📂 Dataset

The project uses an e-commerce transactional dataset for analysis.

The raw dataset is not included in this repository due to its large file size.
The notebooks contain the complete data cleaning, transformation, and analysis workflow.
