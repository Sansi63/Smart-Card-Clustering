# Customer Segmentation Using K-Means and Agglomerative Clustering

## Project Overview

This project applies **K-Means Clustering and also Agglomerative Clustering** to segment customers based on demographic and purchasing behavior data.

The main objectives of this project are:

- Identify distinct customer groups
- Improve targeted marketing strategies
- Increase campaign effectiveness
- Support data-driven business decisions

---

## Dataset Description

The dataset contains demographic, behavioral, and campaign-related customer features.

### Demographic Features

- **Income** – Annual customer income
- **Age** – Customer age
- **Marital Status** – Married / Single
- **Education Level** – Undergraduate / Graduate / Postgraduate
- **Total_Children** – Number of children

### Behavioral Features

- **Recency** – Days since last purchase
- **NumDealsPurchases** – Purchases made using discounts
- **NumWebPurchases** – Online purchases
- **NumCatalogPurchases** – Catalog purchases
- **NumStorePurchases** – In-store purchases
- **NumWebVisitsMonth** – Website visits per month
- **Complain** – Complaint indicator (0/1)
- **Response** – Campaign response indicator (0/1)

### Engineered Feature

- **Total_Spending** – Total amount spent by the customer

---

## Methodology

### 1. Data Preprocessing

- Handled missing values
- Encoded categorical variables
- Standardized numerical features
- Created aggregated spending feature

### 2. Clustering Model

- Algorithm used: **K-Means and Agglomerative**
- Optimal number of clusters determined using:
  - Elbow Method
  - Silhouette Score
- Final model built with **4 clusters**

---

## Cluster Profiles

### Cluster 0 – Mid-Income Traditional Families

- Moderate income (~39K)
- Moderate spending (~226)
- Higher number of children
- Mostly married
- Low campaign response rate

**Strategy:** Loyalty programs and family bundle promotions.

---

### Cluster 1 – Affluent Single Big Spenders

- High income (~66K)
- High spending (~1,019)
- Fewer children
- Strong online purchasing behavior
- Highest campaign response rate

**Strategy:** Premium products and personalized marketing.

---

### Cluster 2 – Low-Income Light Spenders

- Lowest income (~33K)
- Lowest spending (~91)
- High website visits but low purchasing
- Mostly single customers

**Strategy:** Discounts, coupons, and conversion optimization.

---

### Cluster 3 – Wealthy High-Value Married Shoppers

- Highest income (~73K)
- Highest spending (~1,258)
- Strong multi-channel purchasing behavior
- Mostly married customers

**Strategy:** Luxury positioning, upselling, and exclusive offers.

---

## Key Insights

- Clusters 1 and 3 generate the highest revenue.
- Cluster 2 shows high traffic but low conversion.
- Cluster 0 benefits from loyalty-based marketing.
- Personalized campaigns significantly improve response rates.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## How to Run the Project

1. Clone the repository:
   git clone <https://github.com/Sansi63/Smart-Card-Clustering/tree/main>

2. Install dependencies:
   pip install pandas numpy scikit-learn matplotlib seaborn

3. Run the notebook or Python script to reproduce the clustering results.

---

## Project Structure

- data/
- notebooks/
- models/
- README.md
- requirements.txt

---

## Author

Sanket Sinha  
Year: 2026