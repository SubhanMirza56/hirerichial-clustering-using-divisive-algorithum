🔹 Divisive Clustering (Top-Down Hierarchical Clustering)
Divisive clustering is a top-down approach where:

All data points start in one big cluster.

The cluster is recursively split into smaller sub-clusters.

Splitting continues until:

A desired number of clusters (k) is reached, or

Each data point is its own cluster, or

A stopping criterion is met (e.g., low variance).

🔍 Key Points:
Opposite of agglomerative clustering (which merges).

Often uses k-means or PCA to decide splits.

Builds a dendrogram, showing how clusters were split.

✅ Good For:
Discovering structure in data with clear splits.

Situations where starting broad and narrowing down makes sense.
