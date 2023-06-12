# Clustering-Algorithm

Library Installation

Clustering Dataset

1. Mini-Batch K-Means
2. K-Means
3. Agglomerative Clustering
4. Affinity Propagation 
5. BIRCH
6. DBSCAN
7. Mean Shift
8. Spectral Clustering
9. Gaussian Mixture Model
10. OPTICS
11. Hierarchical clustering (linkage and dendrogram) 

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

* The linkage and dendrogram functions from scipy.cluster.hierarchy are used for hierarchical clustering and visualization.

The linkage function performs agglomerative hierarchical clustering on a given dataset. It takes the data points as input and computes the linkage matrix, which represents the hierarchical structure of the clusters. The linkage matrix contains information about the merging of clusters at each step of the algorithm.

The dendrogram function is used to visualize the hierarchical clustering result as a dendrogram. It takes the linkage matrix as input and creates a plot that represents the merging of clusters.

Circos Tool

# Performance Metrics

Clustering algorithms are unsupervised learning methods that do not have predefined labels. Therefore, you can assess the quality of clustering results using other metrics that are specific to clustering tasks. Here are a few commonly used metrics for evaluating clustering algorithms:

Silhouette Score:
The Silhouette score measures the compactness and separation of clusters. It ranges from -1 to 1, where higher values indicate better-defined clusters.

The Silhouette Score ranges from -1 to 1, where:

-> A score close to 1 indicates that the data point is well-matched to its own cluster and poorly matched to neighboring clusters. This suggests a good separation between clusters.

-> A score close to 0 indicates that the data point is on or very close to the decision boundary between neighboring clusters.

-> A score close to -1 indicates that the data point is probably assigned to the wrong cluster, as it is more similar to points in a neighboring cluster than its own cluster.

Adjusted Rand Index (ARI):
The ARI measures the similarity between the clustering result and the ground truth labels (if available). It ranges from -1 to 1, where values close to 1 indicate strong agreement between the clusters and the true labels.

Homogeneity, Completeness, and V-measure:
These metrics assess different aspects of clustering quality, including the extent to which each cluster contains only samples from a single true class (homogeneity), the extent to which all samples from a given true class are assigned to the same cluster (completeness), and their harmonic mean (V-measure).
