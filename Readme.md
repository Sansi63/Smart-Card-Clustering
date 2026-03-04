Customer Segmentation Using K-Means Clustering
1. Project Overview

This project performs customer segmentation using K-Means clustering to group customers based on income, spending behavior, purchasing patterns, and demographics.

The objective is to identify distinct customer segments to support:

Targeted marketing strategies

Customer retention improvement

Revenue maximization

Personalized campaign design

2. Dataset Description

The dataset contains customer demographic, behavioral, and campaign response features.

Demographic Variables

Income – Annual income

Age – Customer age

Marital Status – Married / Single

Education Level – Undergraduate / Graduate / Postgraduate

Total_Children – Number of children

Behavioral Variables

Recency – Days since last purchase

NumDealsPurchases – Purchases made using discounts

NumWebPurchases – Online purchases

NumCatalogPurchases – Catalog purchases

NumStorePurchases – In-store purchases

NumWebVisitsMonth – Website visits per month

Complain – Complaint indicator (0/1)

Response – Campaign response indicator (0/1)

Engineered Feature

Total_Spending – Total amount spent by the customer

3. Data Preprocessing

Handled missing values

Encoded categorical variables

Scaled numerical features using standardization

Created Total_Spending feature

Prepared dataset for clustering

4. Clustering Methodology

Algorithm: K-Means

Optimal number of clusters selected using:

Elbow Method

Silhouette Score

Final model trained with 4 clusters

5. Cluster Summary
Cluster 0 – Mid-Income Traditional Families

Moderate income and spending

Higher number of children

Mostly married

Moderate campaign response

Strategy: Loyalty programs and family bundles.

Cluster 1 – Affluent Single Big Spenders

High income

High spending

Fewer children

Highest campaign response

Strategy: Premium products and personalized marketing.

Cluster 2 – Low-Income Light Spenders

Lowest income

Lowest spending

High website visits but low purchases

Strategy: Discounts, coupons, and conversion optimization.

Cluster 3 – Wealthy High-Value Married Shoppers

Highest income

Highest spending

Strong multi-channel purchasing behavior

Strategy: Luxury positioning and upselling.

6. Key Insights

Clusters 1 and 3 generate the highest revenue.

Cluster 2 shows opportunity for better conversion.

Cluster 0 responds well to loyalty-based strategies.

Marketing personalization is critical.

7. Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook