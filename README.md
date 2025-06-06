# KMeans_clustering
📘 Documentation: KMeans Clustering from Scratch with Elbow Method
🔍 Overview:
This project demonstrates a custom implementation of the K-Means Clustering Algorithm using only core Python libraries and scikit-learn’s make_blobs for synthetic data generation. It includes an elbow method visualization to determine the optimal number of clusters.

🧠 KMeans Class Implementation
__init__(self, n_clusters)
Initializes the class with a given number of clusters.

elbow_graph(self, X)
Implements the Elbow Method:

Randomly selects centroids for k values from 1 to 20.

Computes WCSS (Within-Cluster Sum of Squares) by finding the minimum distance of each point to the nearest centroid.

Plots k vs WCSS.
📌 Notes:
Distance calculations are performed using scipy.spatial.distance.cdist.

The implementation avoids using scikit-learn's KMeans, offering full transparency and educational value.

Centroid selection and distance-based assignments are done manually for clear understanding.

