# Use various clustering techniques in colab

**Kmeans Clustering:**
K-means clustering is one of the simplest and popular unsupervised machine learning algorithms.

**How the K-means algorithm works:**
To process the learning data, the K-means algorithm in data mining starts with a first group of randomly selected centroids, which are used as the beginning points for every cluster, and then performs iterative (repetitive) calculations to optimize the positions of the centroids.It halts creating and optimizing clusters when either:
The centroids have stabilized — there is no change in their values because the clustering has been successful.
The defined number of iterations has been achieved.

**Hierarchical  Clustering:**
Hierarchical clustering is an agglomerative (top down) clustering method. As its name suggests, the idea of  this method is to build a hierarchy of clusters, showing relations between the individual members and  merging clusters of data based on similarity. The hierarchical clustering algorithm is only interested in finding the closest relationship at each stage regardless of the degree of similarity.

**How the Hierarchical  algorithm works:**
Hierarchical clustering takes as input a set of points 
 It creates a tree in which the points are leaves and the  internal nodes reveal the similarity structure of the points.
▪ The tree is often called a “dendogram.”
 The method is summarized below:
Place all points into their own clusters
While there is more than one cluster, do Merge the closest pair of clusters
 The behavior of the algorithm depends on how “closest pair of clusters” is defined

**DBSCAN Clustering:**
DBSCAN stands for Density-Based Spatial Clustering of Applications with Noise. he most exciting feature of DBSCAN clustering is that it is robust to outliers. It also does not require the number of clusters to be told beforehand, unlike K-Means, where we have to specify the number of centroids. DBSCAN requires only two parameters: epsilon and minPoints. Epsilon is the radius of the circle to be created around each data point to check the density and minPoints is the minimum number of data points required inside that circle for that data point to be classified as a Core point.

**Gaussian Mixture**
Gaussian Mixture Models are a powerful clustering algorithm.
Gaussian Mixture Models (GMMs) assume that there are a certain number of Gaussian distributions, and each of these distributions represent a cluster. Hence, a Gaussian Mixture Model tends to group the data points belonging to a single distribution together.
