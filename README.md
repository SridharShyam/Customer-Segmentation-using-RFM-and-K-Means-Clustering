# Customer Segmentation Intelligence


## Customer Segmentation using RFM and K-Means Clustering:
A data-driven approach to categorize customers based on behavior using Recency, Frequency, and Monetary value, enhanced with K-Means Clustering.

## Overview:
This project leverages RFM analysis and K-Means clustering to segment customers based on purchasing patterns. The purpose is to uncover actionable customer segments to boost retention, optimize marketing, and maximize customer lifetime value.

## Objective:
Segment customers into logical groups based on their transaction data to:

- Identify valuable and at-risk customers.  
- Personalize marketing strategies.
- Improve customer engagement and profitability.

## Tech Stack:
- Python
- Pandas / NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Google Colab

## Dataset Description:
Original features:
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

Selected features:
- CustomerID
- InvoiceNo
- InvoiceDate
- Quantity
- UnitPrice
- Country

Added features:
- TotalSpend

From this data:
- Recency: Days since last purchase.
- Frequency: Number of purchases.
- Monetary: Total spent.

## RFM Analysis:
Customers are scored 1-5 based on:
- Recency (lower is better)
- Frequency (higher is better)
- Monetary (higher is better)
Scores are combined to create an overall RFM score and category.

## Customer Segmentation using Clustering:
- RFM values are scaled.
- K-Means clustering was applied.
- Optimal k was selected using the elbow method.
- Silhouette Score was used to evaluate clustering.
- Segments include Loyal, At-Risk, Lost, New, and Potential Loyalists.

## Visualizations:
- Boxplots for RFM metrics by cluster.
- Cluster distribution chart.
- Elbow method plot.

## Insights & Results:
- Clear segments formed.
- Identified key groups: "Loyal Customers", "Potential Loyalists", "At-Risk", etc.
- Useful for personalized campaigns and retention efforts.
