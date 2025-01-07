# Unsupervised Learning for International Trade Transactions

## Project Overview

This project explores unsupervised machine learning techniques, specifically clustering, to segment and analyze a dataset of international trade transactions. The primary goal is to identify distinct groups or segments within the data based on their similarities and derive meaningful insights for business applications.

## Data Source

The dataset used in this project is sourced from Kaggle:

- Dataset Name: Imports-Exports-15000
- Link: (Please do not add links)
- Size: 2.69 MB

## Data Description

The dataset contains information about international trade transactions, including details about products, quantities, values, countries, and other relevant attributes.

- Data Type: Panel
- Data Dimension: 16 Variables, 15000 Observations
- Data Variable Types: Numeric and Non-Numeric
- Data Variable Categories: Index, Nominal, Ordinal, Non-Categorical

## Project Objectives

- **Segmentation:** Segment the dataset using unsupervised machine learning clustering algorithms.
- **Cluster Identification:** Identify the appropriate number of segments or clusters.
- **Cluster Characterization:** Determine the characteristics of each segment or cluster.

## Methodology

The project utilizes the following clustering algorithms:

- **K-Means:** A partitioning-based clustering algorithm that aims to group data points into k clusters based on their similarity to cluster centroids.
- **DBSCAN:** A density-based clustering algorithm that identifies clusters based on the density of data points in a region.

**Steps:**

1. **Data Preprocessing:** Relevant variables are selected, and the data is scaled using MinMaxScaler and encoded using Ordinal Encoder.
2. **Clustering:** K-Means and DBSCAN algorithms are applied with different parameters.
3. **Cluster Evaluation:** The Silhouette Score and Davies-Bouldin Score are calculated to assess the quality of clusters.
4. **Cluster Selection:** The optimal number of clusters is chosen based on evaluation metrics.
5. **Cluster Characterization:** The characteristics of each cluster are analyzed using descriptive statistics and visualizations.

## Results

- **Optimal Number of Clusters:** The analysis suggests that 5 clusters (K-Means) and 3 clusters (DBSCAN) are the most appropriate for the dataset.
- **Cluster Characteristics:** Each cluster exhibits distinct characteristics based on the variables used for clustering, such as quantity, value, and weight.

## Managerial Insights

- **Understanding Trade Patterns:** The identified clusters provide insights into different trade activities, such as high-value transactions, bulk commodity trading, and seasonal trends.
- **Targeted Business Strategies:** Businesses can use cluster information to develop targeted strategies for different customer segments, including logistics solutions, pricing models, and product recommendations.
- **Risk Management:** Identifying clusters with unusual or potentially risky characteristics aids in risk mitigation and fraud detection.
- **Operational Efficiency:** Businesses can optimize their operations based on the characteristics of different trade segments, improving inventory management, shipping routes, and customs procedures.

## Authors

- Soumyadeep Das - FORE School of Management - PGDM (Big Data Analysis)(055048)
- Suvra Datta Banik - FORE School of Management - PGDM (Big Data Analysis | Finance)(0550049)
- Group Number: 31
