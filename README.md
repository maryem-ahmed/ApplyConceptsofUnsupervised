This Notebook demonstrates the implementation of the K-Means clustering algorithm, PCA , Dimensional Reduction from scratch using Python and NumPy.
The dataset used is ex7data2.mat, which contains 2D data points suitable for clustering tasks.
--> Key Functions
init_centroids(x, k): Initializes k centroids randomly from the dataset.
findClosestCentroids(x, centroids): Assigns each data point to the nearest centroid.
computeCentroids(x, idx, k): Updates centroids based on the mean of assigned points.
run_KMeans(x, initial_centroids, max_iters): Runs the K-Means algorithm for a specified number of iterations.
--------------------------------------------------------
Results
The notebook includes visualizations showing:
The initial random centroids.
Cluster assignments and centroid positions after each iteration.
Final clusters and converged centroids.
--------------------------------------------------------
Notes
The number of clusters (k) is set to 3.
The algorithm runs for a maximum of 6 iterations (for demonstration purposes).
Visualizations are generated using Matplotlib to observe the clustering process.
