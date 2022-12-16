# Clustering, an unsupervised learning

![image](https://user-images.githubusercontent.com/106495355/207197087-ec5d229a-51a0-4aa8-bf99-8753941b4ce2.png)

## Cluster Methods
1. K-means:k
2. Hierarchical:break point
3. DBSCAN: eps, minpts
4. GMM: k

![image](https://user-images.githubusercontent.com/106495355/207230928-d720a247-ff06-4b02-a213-120b894c06c8.png)
![image](https://user-images.githubusercontent.com/106495355/207231030-52de91ee-b370-4fa5-9727-447c0974a75b.png)
![image](https://user-images.githubusercontent.com/106495355/207231097-7cde08a6-fe36-48da-b8c9-9962ef102384.png)

### K-means
1. Fast, easy to understand
2. User specifies the desired number of clusters, K
3. Algo assigns each instance to exactly one of the K clusters.

### How to decide how many clusters?
1. Hyperparameter tuning 
2. Business Requirements

## Popular Clustering Algo

![image](https://user-images.githubusercontent.com/106495355/207197422-65e0224e-c25b-4d10-b786-c74d3460b20f.png)

### Distance Metrics
Distance Metrics measures how "far apart" two instances are from each other

Common distance metrics
1. Euclidean：the straight line between two instances
2. Cosine : measure the cosine of the angle between two vectors
3. Manhattan : measure the length of right angled lines between two points
4. Chebyshev :
5. Canberra
6. Pearson Correlation
7. Hamming
8. Jaccard

![image](https://user-images.githubusercontent.com/106495355/207229755-3608de91-c3e0-450a-b271-a0cf5dc937ae.png)

### Which one is the best?
1. Euclidean is good all-purpose, but not good with lots of features
2. Cosine is good when absolute value is not important

![image](https://user-images.githubusercontent.com/106495355/207230086-643319a3-6c24-41e3-b94f-85fa5ab6e83d.png)
![image](https://user-images.githubusercontent.com/106495355/207230136-be52fd11-f88c-4abe-b4c8-fa419c02680a.png)
![image](https://user-images.githubusercontent.com/106495355/207230189-8659d03a-01cb-48e5-820a-e8c402128cbc.png)
![image](https://user-images.githubusercontent.com/106495355/207230376-ab20fcbb-f818-42d7-a6c5-d40daa5a31c5.png)

### DBSCAN
Density-based spatial clustering of applications with noise
1. Discovers of clusers with arbitrary shape
2. No prior knowledge of the number of clusters required
3. Good efficiency on large data sets
4. Two hyper parameters: MinPts and Eps
- MinPts: at least 3, or at least the number of features +1
- Eps: Using the elbow in a k-distance graph

### How DBSCAN minimize outliers effects?
1. Clusters have a higher density of points than noise.
2. Noise has lower density than clusters.
3. Algo looks for sets of points that are "dense".

### Hierarchical Clustering
aka, Agglomerative Clustering
Iteratively joins instances to build a hierarchy of clusters
Resulting hierarchy is shown as a dendrogram
Hyperparameters : distance metirc, linkage function
![image](https://user-images.githubusercontent.com/106495355/207230759-3f606ef6-de82-430a-9d00-a7bf2b1d8838.png)

### Evaluating Metrics
### Internal Validation Metrics:
1. Calinski-Harabasz Index: Measures density of clusters, higher = better, range >0
2. Silhouette Coefficient: Measures distance between clusters, higher = better, 1>range>0 




