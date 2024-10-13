# Segmentation_with_KMeans_Clustering

### Overview
#### This project performs a K-Means clustering analysis on raw census data of Bihar, India, to segment regions based on the percentage of households with electricity and televisions. The goal is to identify factors that influence television ownership in different areas. The K-Means clustering method is used to group districts or blocks with similar patterns of household electricity access and television ownership, providing insights into what drives television ownership across Bihar.

### How K-Means Clustering Works
Initialize Centroids: Choose K initial centroids randomly or based on some heuristic (e.g., K-Means++).

Assign Data Points to Clusters: Each data point is assigned to the nearest centroid. This forms K clusters.

Recompute Centroids: Once all points are assigned to clusters, recompute the centroids of the clusters as the mean of all data points in the cluster.

Repeat: Repeat steps 2 and 3 until convergence, i.e., when the centroids no longer change or the algorithm has iterated a maximum number of times.

Final Clusters: Once convergence is reached, the final centroids are the centers of the clusters, and each data point is assigned to one of the K clusters.
