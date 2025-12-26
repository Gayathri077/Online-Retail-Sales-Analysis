# Online Retail Sales & Customer Behavior Analysis

## Business Objective
To analyze online retail transaction data in order to identify key revenue drivers, sales trends, and customer purchasing behavior. The goal is to support data-driven decision-making for improving revenue performance and understanding cancellation patterns.

---

## Dataset Overview
The dataset contains transactional-level retail data with the following key fields:

- **Invoice**: Unique identifier for each transaction
- **InvoiceDate**: Date and time of purchase
- **CustomerID**: Unique identifier for customers (may contain missing values)
- **Country**: Country where the transaction occurred
- **Quantity**: Number of units purchased
- **UnitPrice**: Price per unit of product

---

## Data Preparation
- Calculated revenue using quantity and unit price for sales performance analysis
- Retained cancelled and returned transactions to analyze cancellation behavior
- Preserved transactions with missing CustomerID to maintain complete transactional flow
- Checked for duplicate invoice-product records to ensure accurate aggregation

---

## Feature Engineering
- Created revenue-based metrics to evaluate business performance
- Derived time-based features to analyze sales trends and seasonality
- Examined invoice-level frequency and recency patterns to understand customer behavior

---

## Analysis Performed
- Identified top revenue-contributing customers and transactions
- Analyzed cancellation and return patterns to assess operational impact
- Evaluated sales distribution across countries and time periods
- Assessed customer purchasing behavior using transactional history

---

## Key Insights
- A small percentage of customers contribute a disproportionate share of total revenue
- Cancelled and returned transactions have a measurable impact on overall revenue
- Repeat purchasing behavior indicates opportunities for targeted retention strategies

---

## Tools Used
- Python (Pandas, NumPy)
- Jupyter Notebook
- Excel

---

## Conclusion
This analysis provides insights into revenue concentration, sales behavior, and cancellation impact, helping businesses optimize decision-making related to customer retention and operational efficiency.
