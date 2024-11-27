# Clustering-Algorithm-

# ris Dataset Clustering
This repository contains Python code to implement KMeans Clustering and Hierarchical Clustering on the well-known Iris dataset from the sklearn library. The code demonstrates how to apply unsupervised learning algorithms to group the iris flowers based on their features.

# Table of Contents
1. Description
2. Algorithms Implemented
   *. KMeans Clustering
   *. Hierarchical Clustering
3. Installation
4. Usage
5. Visualizations
6. License
   
# Description
The Iris dataset is a famous dataset in machine learning, containing 150 data points of iris flowers. Each data point has four features:

*. Sepal length
*. Sepal width
*. Petal length
*. Petal width

These features are used to classify the flowers into one of three species: Setosa, Versicolor, and Virginica. In this project, we perform unsupervised clustering using two algorithms: KMeans Clustering and Agglomerative (Hierarchical) Clustering.

# Algorithms Implemented

# KMeans Clustering
KMeans Clustering is an iterative algorithm that partitions the dataset into k clusters. The algorithm works by:

1. Selecting k initial centroids (cluster centers).
2. Assigning data points to the nearest centroid.
3. Recalculating the centroids based on the assigned points.
4. Repeating steps 2 and 3 until convergence.
   
In this project, we use KMeans clustering to group the iris flowers into 3 clusters, as the dataset has 3 species.

# Hierarchical Clustering
Hierarchical Clustering builds a hierarchy of clusters. In this implementation, Agglomerative Clustering (bottom-up approach) is used. The algorithm:

1. Starts with each data point as its own cluster.
2. Iteratively merges the two closest clusters until all points belong to a single cluster or the desired number of clusters is reached.
   
This method does not require the number of clusters to be specified upfront and is represented by a dendrogram that visually shows the clustering process.

# Visualizations
Both clustering algorithms generate visualizations that show how the Iris flowers are grouped into clusters. For simplicity, only the first two features (sepal length and sepal width) are used for the 2D scatter plots.

# KMeans Clustering: A scatter plot where each data point is colored according to its assigned cluster.
# Agglomerative Clustering: A similar scatter plot showing the clusters formed by hierarchical clustering.

The color of the points in the plot represents the clusters formed by the algorithm.
