# CryptoClustering
A repository for the Module 19 Challenge: Crypto Clustering. This project uses unsupervised learning techniques (K-Means and PCA) to analyze cryptocurrency market data.

Module 19 Challenge: Crypto Clustering with K-Means and PCA
Overview
This project uses K-Means clustering and Principal Component Analysis (PCA) to analyze and group cryptocurrencies based on their market performance. The clustering process explores the original dataset and a reduced-dimension dataset created using PCA, providing insights into cryptocurrency behaviors and identifying outliers.

Key Features
Data Preprocessing:
Scaled cryptocurrency performance data for better comparability.
K-Means Clustering:
Determined the optimal number of clusters (k=4) using the Elbow Method.
Performed clustering on both the original and PCA-reduced data.
Dimensionality Reduction with PCA:
Reduced dataset features to three principal components while retaining ~89% of variance.
Visualization:
Scatter plots comparing clusters for both original and PCA-transformed data.
Composite plots contrasting Elbow curves for both datasets.
Observations
Outliers were identified in the clustering process, with one cluster containing a single cryptocurrency across datasets.
PCA simplified the clustering process, improving visualization while maintaining clustering consistency.
How to Use
Clone the repository.
Open the crypto_clustering.ipynb notebook in Jupyter Lab.
Run all cells sequentially to reproduce the results.
Files
crypto_clustering.ipynb: Main notebook with data processing, clustering, and visualization.
Resources/crypto_market_data.csv: Dataset of cryptocurrency market performance.
Tools and Libraries
Python
Pandas, scikit-learn, hvplot
Jupyter Lab
Author
This project was completed as part of the UC Berkeley Data Analytics Bootcamp.

