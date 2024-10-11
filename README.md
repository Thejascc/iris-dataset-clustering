# Iris Dataset Clustering Analysis

## Objective
This project aims to evaluate clustering techniques by applying them to the **Iris dataset** from `sklearn`. The focus is on implementing and comparing two popular clustering algorithms: **KMeans** and **Hierarchical Clustering**.

## Dataset
The dataset used is the Iris dataset, available from the `sklearn` library, which contains information about three species of iris flowers. The species column was dropped as this is an unsupervised learning (clustering) problem.

## Key Components

### 1. Loading and Preprocessing
- Loaded the Iris dataset from `sklearn`.
- Dropped the species column and standardized the data.

### 2. Clustering Algorithms 

#### A) KMeans Clustering
- **Description**: KMeans clustering partitions the data into `K` clusters by minimizing the distance between points and centroids.
- **Why KMeans**: Suitable for the Iris dataset due to its ability to find natural groupings in data.
- **Implementation**: Applied KMeans clustering and visualized the resulting clusters along with centroids.

#### B) Hierarchical Clustering
- **Description**: Hierarchical clustering builds a hierarchy of clusters through an agglomerative approach.
- **Why Hierarchical**: It doesn’t require predefining the number of clusters and provides a detailed dendrogram.
- **Implementation**: Applied hierarchical clustering and visualized clusters using a dendrogram and scatter plot.

## How to Run
1. Clone this repository.
2. Install the required libraries:
