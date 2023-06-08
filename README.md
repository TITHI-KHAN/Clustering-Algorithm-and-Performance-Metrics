# Clustering-Algorithm

1. Library Installation
2. Clustering Dataset
3. Affinity Propagation
4. Agglomerative Clustering
5. BIRCH
6. DBSCAN
7. K-Means
8. Mini-Batch K-Means
9. Mean Shift
10. OPTICS
11. Spectral Clustering
12. Gaussian Mixture Model

Each algorithm offers a different approach to the challenge of discovering natural groups in data.

# For a good starting point on this topic, see:
https://scikit-learn.org/stable/modules/clustering.html

1. MiniBatchKMeans: A variant of K-means that uses mini-batches to reduce computation time.
2. KMeans: The classic K-means clustering algorithm.
3. AgglomerativeClustering: Performs hierarchical clustering using different linkage criteria.
4. AffinityPropagation: Clusters data by sending messages between pairs of samples.
5. Birch: Builds a tree-based structure to perform clustering.
6. DBSCAN: Density-based spatial clustering of applications with noise.
7. MeanShift: Clustering algorithm based on the idea of moving points towards the densest regions.
8. SpectralClustering: Applies clustering to a low-dimensional affinity matrix obtained from data.
9. GaussianMixture: Fits a mixture of Gaussian distributions to the data.
10. OPTICS: Density-based clustering algorithm that can handle varying densities.

# The linkage and dendrogram functions from scipy.cluster.hierarchy are used for hierarchical clustering and visualization.

The linkage function performs agglomerative hierarchical clustering on a given dataset. It takes the data points as input and computes the linkage matrix, which represents the hierarchical structure of the clusters. The linkage matrix contains information about the merging of clusters at each step of the algorithm.

The dendrogram function is used to visualize the hierarchical clustering result as a dendrogram. It takes the linkage matrix as input and creates a plot that represents the merging of clusters.

Circos Tool
