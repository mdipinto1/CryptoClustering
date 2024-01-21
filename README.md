# CryptoClustering

## Cryptocurrency Market Analysis

This project involves analyzing cryptocurrency market data using machine learning techniques. The primary goal is to cluster cryptocurrencies based on various market characteristics to identify patterns and relationships.

## Project Structure

The code is divided into several sections, each performing specific tasks:

1. **Data Loading and Exploration**: The cryptocurrency market data is loaded into a Pandas DataFrame. Basic data exploration tasks such as displaying sample data and generating summary statistics are performed.

2. **Data Preparation**: The data is normalized using `StandardScaler` from scikit-learn, essential for effective clustering.

3. **K-Means Clustering**: The optimal number of clusters (`k`) is determined using the Elbow Method. K-Means clustering is then applied to group the cryptocurrencies into clusters.

4. **Principal Component Analysis (PCA)**: PCA is used to reduce the dimensionality of the dataset, retaining essential features. The optimal number of clusters is again determined using the Elbow Method on the PCA-transformed data, followed by K-Means clustering.

5. **Data Visualization**: Scatter plots are used to visualize the clustering results.