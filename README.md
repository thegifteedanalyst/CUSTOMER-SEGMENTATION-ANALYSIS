## Customer Segmentation Using RFM Analysis for an E-commerce Company
 
 # Business Problem

An e-commerce company was experiencing flat revenue growth despite increasing customer acquisition. Marketing efforts were broad and generic, leading to:

i.Low customer retention
ii.Inefficient ad spend
iii.Poor personalization
iv.Inability to identify high-value customers

The business needed a data-driven way to understand customer behavior and target users more effectively.

# Objective

To segment customers based on purchasing behavior and provide actionable insights to:

i.Improve customer retention
ii.Increase repeat purchases
iii.Optimize marketing campaigns
iv.Identify high-value and at-risk customers

# Data Sources
Customers dataset
Orders dataset
Products dataset

These were merged to create a unified transactional dataset.

# Approach: RFM Analysis

Customers were segmented using RFM (Recency, Frequency, Monetary):

Recency (R): Days since last purchase
Frequency (F): Total number of orders
Monetary (M): Total amount spent

# Steps Performed
i.Data cleaning and preprocessing
ii.Merging datasets into a single analytical table
iii.Aggregating customer-level metrics

Calculating:
Recency (based on last purchase date)
Frequency (total orders)
Monetary (total spend)
Assigning scores (1–5) using quantiles
Creating combined RFM scores
Segmenting customers into behavioral groups

# Customer Segments Identified
i.Loyal Customers:High frequency and recent purchases
ii.New Customers: Recently acquired but low purchase frequency
iii.Potential Loyalists:Moderate engagement with growth potential
iv.At-Risk Customers:Previously active but not recent
v.Lost Customers:Low frequency and long inactivity

# Key Insights
A significant portion of customers fell into the Potential Loyalist category → strong upsell opportunity
At-Risk customers represented a hidden revenue leakage
Loyal customers, though fewer, contributed disproportionately to revenue
New customers required onboarding strategies to increase retention

## Business Recommendations
1. Retention Strategy
Target At-Risk customers with:
Personalized discounts
Email re-engagement campaigns
2. Revenue Growth
Upsell and cross-sell to Potential Loyalists
Introduce loyalty programs for Loyal Customers
3. Customer Experience
Improve onboarding for New Customers
Use personalized product recommendations
4. Marketing Optimization
Shift from generic campaigns to segment-based targeting
Allocate more budget to high-value segments

# Impact (Expected Business Value)
1. Increase in customer retention rate
2. Higher customer lifetime value (CLV)
3. Improved marketing ROI
4. Growth in repeat purchases

# Technical Stack
Python (Pandas, NumPy)
Data Visualization: Matplotlib, Seaborn
Analytics Technique: RFM Segmentation

# Conclusion
Generic marketing treats all customers the same.
This project proves that behavioral segmentation unlocks hidden revenue opportunities by enabling:

1. Smarter targeting
2. Better retention
3. Higher profitability
