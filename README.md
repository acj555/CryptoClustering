# Crypto Clustering with K-Means and PCA

This project uses unsupervised machine learning to analyze and group cryptocurrencies based on their price change behavior across multiple timeframes.

## Overview

The analysis was completed as part of a data analytics course focused on clustering and dimensionality reduction. The main goals of the project were to:
- Normalize crypto market data
- Use the Elbow Method to identify the optimal number of clusters
- Apply K-Means clustering to group similar cryptocurrencies
- Use Principal Component Analysis (PCA) to reduce the number of features while preserving most of the variance
- Visualize and compare clustering results before and after dimensionality reduction

## Data

The dataset includes percentage price changes for a set of cryptocurrencies over the following timeframes:
- 24 hours
- 7 days
- 14 days
- 30 days
- 60 days
- 200 days
- 1 year

## Key Techniques Used

- **StandardScaler** for feature normalization  
- **KMeans** for unsupervised clustering  
- **Elbow Method** to determine optimal `k`  
- **PCA (Principal Component Analysis)** for dimensionality reduction  
- **hvPlot** for interactive visualizations  

## Results

- The Elbow Method suggested that **4 clusters** was the best choice for both the original and PCA-transformed data.
- PCA retained approximately **89.5%** of the original variance using just 3 components.
- Cluster plots from both methods produced similar results, but PCA made the structure slightly easier to interpret.

## Final Thoughts

This project demonstrated how PCA can simplify complex datasets while preserving important patterns, and how clustering algorithms can reveal hidden groupings in financial data.

