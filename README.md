# Clustering

![image](https://github.com/TITHI-KHAN/K-Means-Clustering-/assets/65033964/cdd5ca66-d0d0-48a7-99b1-55220f289ae9)

Clustering is a widely used technique in the industry. It is actually being used in almost every domain, ranging from banking to recommendation engines, document clustering to image segmentation.

▪ Customer Segmentation

▪ Document Clustering

▪ Image Segmentation

▪ Recommendation Engines

# K-Means-Clustering

K-means clustering is a popular unsupervised machine learning algorithm used to partition a dataset into a predetermined number of clusters. The algorithm aims to minimize the within-cluster sum of squares, which measures the squared Euclidean distance between each data point and the centroid of its assigned cluster. Let's break down the mathematical steps involved in the K-means clustering algorithm:

**1. Initialization:**
- Select the number of clusters, K.
- Randomly initialize K centroids in the feature space or use a specific initialization strategy.
  
**2. Assigning data points to clusters:**
- Calculate the Euclidean distance between each data point and all centroids.
- Assign each data point to the cluster with the nearest centroid, forming K clusters.
  
**3. Updating centroids:**
- Calculate the new centroid for each cluster by taking the mean of all data points assigned to that cluster.
- The centroid represents the center of the cluster in the feature space.
  
**4. Iterative process:**
- Repeat steps 2 and 3 until convergence or a predefined stopping criterion is met.
- Convergence occurs when the centroids no longer change significantly or when the maximum number of iterations is reached.

The algorithm converges to a local minimum of the within-cluster sum of squares, but it does not guarantee convergence to the global minimum. Different random initializations may result in different clustering outcomes. The mathematical objective function for K-means clustering can be expressed as:

![image](https://github.com/TITHI-KHAN/K-Means-Clustering-/assets/65033964/56f390ab-d915-4e3c-8da7-e99f8968e7a4)

The goal of the algorithm is to minimize this objective function by iteratively updating the cluster assignments and the centroids. When the algorithm converges, the centroids represent the final clustering
solution.

# The k-means cluster algorithm mainly performs two important tasks:

▪ Determines the best value for K center points or centroids by an iterative process.

▪ Assigns each data point to its closest k-center (also called centroid). Those data points which are near to the particular k-center, create a cluster.

# Elbow Method for optimal value of k in KMeans

![image](https://github.com/TITHI-KHAN/K-Means-Clustering-/assets/65033964/570ed7b3-6baa-410b-8296-55549ebb9978)

# How does the K-Means Algorithm Work?

The working of the K-Means algorithm is explained in the below steps:
▪ Step-1: Select the number K to decide the number of clusters.
▪ Step-2: Select random K points or centroids.
▪ Step-3: Assign each data point to their closest centroid, which will form the predefined K clusters.
▪ Step-4: Calculate the variance and place a new centroid of each cluster.
▪ Step-5: Repeat the third steps, which means reassign each data point to the new closest centroid of each cluster.
▪ Step-6: If any reassignment occurs, then go to step-4 else go to FINISH.
▪ Step-7: The model is ready.

# Perform K-Means Cluster

Assume, we have two variables M1 and M2. The X & Y axis scatter plot of these 2 variables is given below:

![image](https://github.com/TITHI-KHAN/K-Means-Clustering-/assets/65033964/2e95830e-2b1b-496f-850d-8d883d5ed365)

![image](https://github.com/TITHI-KHAN/K-Means-Clustering-/assets/65033964/5a552a74-92ee-424e-b2b2-3eb77f8555ce)

![image](https://github.com/TITHI-KHAN/K-Means-Clustering-/assets/65033964/6c66f420-d899-47e8-ad97-10659cda533c)






