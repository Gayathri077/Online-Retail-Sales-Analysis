# Online Retail Sales Analysis

## Business Objective
To analyze online retail transaction data to identify key revenue drivers, customer purchasing patterns, and sales trends, and translate these insights into actionable strategies to improve revenue growth and customer retention.

## Dataset Overview
The dataset contains transactional records from an online retail business. Each row represents a single product-level transaction within an invoice, including purchase date, quantity, pricing, customer, and geographic information.

## Data Cleaning & Preprocessing
- Removed transactions with missing CustomerID to enable accurate customer-level analysis.
- Excluded transactions with negative quantity or zero unit price as cancellations or returns to avoid revenue distortion.
- Removed duplicate invoice–product records to ensure correct aggregation of sales data.

## Feature Engineering
- Created a revenue metric using quantity and unit price.
- Derived time-based features (month, year) to analyze seasonality and trends.
- Built RFM (Recency, Frequency, Monetary) metrics to segment customers based on purchasing behavior.

## Customer Segmentation (RFM Analysis)
Customers were segmented using the RFM framework to identify high-value, loyal, and low-engagement customers based on recency of purchase, purchase frequency, and total revenue contribution.

## Key Insights
- A small percentage of customers contribute the majority of total revenue.
- Repeat and loyal customers generate significantly higher revenue than one-time buyers.
- A notable portion of customers shows low engagement, indicating reactivation opportunities.

## Business Recommendations
- Prioritize retention strategies for high-value and loyal customers.
- Run targeted re-engagement campaigns for inactive customer segments.
- Allocate marketing resources based on customer segment value rather than uniform distribution.

## Limitations
- Profitability analysis was not included.
- Returns and cancellations were excluded from detailed analysis.
- Customer lifetime value was not calculated.

## Future Improvements
- Add CLV and cohort analysis.
- Analyze cancellations and returns separately.
- Create a business dashboard for stakeholders.
