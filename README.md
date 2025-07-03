# Customer Segmentation for Indian Bank

This bank customer segmentation was performed following data cleaning and initial EDA (not shown). RFM scoring and K-means clustering were applied to identify distinct customer groups based on behavioral and demographic characteristics. The results support targeted marketing strategies, reduce churn risk, and enable the design of personalized banking services.


# Data Source
This project use the [Bank Customer Segmentation (1M+ Transactions)](https://www.kaggle.com/datasets/shivamb/bank-customer-segmentation/data) from Kaggle.

# Overview
- **RFM Analysis** (Recency, Frequency, Monetary) to assess customer value.
- **K-Means Clustering** to group customers based on behavioral and demographic characteristics.
- Actionable insights for improving customer engagement and retention.


# Tools & Libraries
- **R** (`tidyverse`, `ggplot2`, `cluster`, `factoextra`)
- **RStudio** for development
- **K-Means** for clustering
- **PCA** for visualization

# Key Findings

- Identified 4 customer segments:

  - **Cluster 1 - Small, High Value**: A small but highly valuable group of older customers with high account balances and spending. They engage less frequently but contribute significantly.
  - **Cluster 2 - Inactive Males**: The largest segment, dominated by male customers with low recent activity, low frequency and low value. They show signs of disengagement.
  - **Cluster 3 - Active Low Spender**: A tiny group of younger, highly engaged customers. They transact frequently and recently, but contribute low monetary value. Their loyalty presents upsell opportunities.
  - **Cluster 4 - Hibernating Females**: A mid-sized group of the youngest, all-female customers with low engagement and value. They are largely inactive but may respond to targeted offers.

# Live Demo
[View HTML Report]
