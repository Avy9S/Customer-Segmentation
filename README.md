# Customer Segmentation using RFM Analysis and K-Means Clustering

## Overview

Understanding customer purchasing behavior is essential for improving customer retention, increasing revenue, and developing effective marketing strategies. This project performs customer segmentation using the Online Retail II dataset by combining RFM (Recency, Frequency, Monetary) analysis with K-Means clustering.

The workflow includes data preprocessing, feature engineering, cluster evaluation, dimensionality reduction, and customer profiling to identify distinct customer segments.

---

## Objectives

- Clean and preprocess retail transaction data.
- Construct RFM features to quantify customer purchasing behavior.
- Engineer additional customer metrics such as Average Order Value.
- Identify optimal customer clusters using K-Means clustering.
- Interpret customer segments for business applications.

---

## Dataset

The project uses the **Online Retail II** dataset containing historical customer transactions.

Key attributes include:

- Invoice Number
- Customer ID
- Invoice Date
- Product Description
- Quantity
- Unit Price
- Country

---

## Feature Engineering

The following customer-level features were created:

- **Recency** – Days since the customer's most recent purchase.
- **Frequency** – Number of unique purchases.
- **Monetary** – Total customer spending.
- **Average Order Value** – Average spending per purchase.

All numerical features were standardized using StandardScaler before clustering.

---

## Methodology

The project follows the workflow below:

1. Data Cleaning
2. RFM Feature Engineering
3. Feature Scaling
4. Elbow Method for cluster selection
5. Silhouette Score evaluation
6. K-Means Clustering
7. PCA visualization
8. Cluster Profiling

---

## Model Evaluation

The clustering model was evaluated using:

- Elbow Method
- Silhouette Score

The resulting customer clusters were analyzed using average RFM values to understand purchasing behavior.

---

## Key Findings

The clustering process identified four distinct customer groups with varying purchasing characteristics.

The customer profiles can support:

- Targeted marketing campaigns
- Customer retention initiatives
- Loyalty program design
- Personalized product recommendations
- High-value customer identification

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## Repository Structure

```
data/
notebooks/
images/
README.md
requirements.txt
```

---

## Future Improvements

- Compare K-Means with Gaussian Mixture Models and DBSCAN.
- Build interactive customer dashboards using Power BI.
- Incorporate Customer Lifetime Value (CLV).
- Automate the segmentation pipeline.

---

## Author

Avisya Samal
