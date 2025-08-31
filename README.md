Customer Segmentation for Targeted Marketing
Project Overview
This project analyzes e-commerce transaction data to segment customers into distinct groups. The goal is to move from a generic marketing approach to personalized, high-impact campaigns tailored to specific customer behaviors, ultimately fostering loyalty and driving revenue growth.

The analysis is contained within the customer_analysis.ipynb Jupyter Notebook.

Techniques - We perform two primary types of customer segmentation:

1. RFM (Recency, Frequency, Monetary) Analysis

Customers are scored and grouped based on their transaction history:

Recency: How recently they purchased.
Frequency: How often they purchase.
Monetary: How much they spend.

This results in intuitive segments like "Champions," "Loyal Customers," "Promising," and "At Risk."

2. K-Means Clustering - Customers are clustered into four distinct groups based on behavioral metrics:

Total Purchase Amount
Average Purchase Amount
Total Returns
Churn Status

This analysis reveals key personas such as "High-Value, Active Champions," "High-Value, Churned Customers," and "At-Risk, High-Volume Customers."

Strategic Recommendations
Based on the identified segments, the analysis concludes with actionable marketing strategies for each group, including:

Loyalty & Reward Programs for top-tier customers.
Win-Back Campaigns for valuable customers who have churned.
Proactive Retention & Feedback campaigns for at-risk groups.
Upsell & Cross-sell opportunities for loyal, lower-spending customers.
And More!

Project Structure: 

your-project-folder/
├── customer_analysis_enriched.ipynb
└── data/
    └── ecommerce_customer_data_large.csv


Required Libraries:

pandas scikit-learn matplotlib seaborn jupyter


Run the cells sequentially to see the analysis.

