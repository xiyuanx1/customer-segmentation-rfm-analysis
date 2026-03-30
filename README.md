# Customer Segmentation Analysis for Online Retail

## Project Overview
This project analyzes online retail transaction data to understand customer purchasing behavior and identify high-value customer segments.

The analysis combines RFM (Recency, Frequency, Monetary) segmentation and revenue concentration (Pareto) analysis to support business decisions related to customer retention, product prioritization, and revenue growth.

## Dataset
- Source: Online Retail transaction dataset
- Records: 500,000+ transaction rows before cleaning
- Key fields: InvoiceNo, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## Tools
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Main Steps
1. Loaded and cleaned transaction data
2. Removed missing CustomerID and invalid transactions (e.g., negative quantities)
3. Created TotalPrice as transaction-level revenue
4. Analyzed overall sales patterns and product-level revenue
5. Conducted Pareto analysis to evaluate revenue concentration across products
6. Built RFM metrics at the customer level
7. Segmented customers into Best, Loyal, Lost, and Other groups
8. Compared segment behavior and summarized insights

## Key Findings
- Revenue is highly concentrated among a relatively small group of products
- The top 10% of products contribute about 62% of total revenue
- The top 20% of products contribute close to 80% of total revenue
- Best Customers show the highest spending, highest purchase frequency, and lowest recency
- Loyal Customers form the largest customer segment and generate stable revenue
- Lost Customers show low recent activity and may require reactivation strategies

## Business Value
- Helps identify high-value customers for targeted marketing and retention strategies
- Supports prioritization of top-performing products for inventory and promotion
- Provides a data-driven approach to customer segmentation and revenue analysis