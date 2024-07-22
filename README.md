# K-Means Clustering Implementation

This repository contains the implementation of the k-means clustering algorithm from scratch as part of my week 2 assignment during my internship at Prodigy Infotech.

## Overview

The k-means clustering algorithm is a popular unsupervised machine learning algorithm used to partition a dataset into `k` clusters, where each data point belongs to the cluster with the nearest mean. This implementation performs the following steps:

1. **Data Loading and Preparation**: Load customer data from a CSV file and prepare it for clustering.
2. **Cluster Initialization**: Initialize cluster centers randomly within the range of the data.
3. **E-Step (Expectation Step)**: Assign each data point to the nearest cluster center.
4. **M-Step (Maximization Step)**: Update the cluster centers as the mean of the assigned points.
5. **Iteration**: Repeat the E-step and M-step until the cluster centers converge.

## Files

- `kmeans_clustering.py`: Contains the full implementation of the k-means clustering algorithm.
- `Mall_Customers.csv`: The dataset used for clustering. This dataset contains information about customers, including their annual income and spending score.

## Implementation Details

### Dependencies

- numpy
- pandas
- matplotlib
- scikit-learn




