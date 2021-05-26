# Clustering
Hierarchical Clustering can be done by two methods
1. Agglomerative: Bottom --> Up approach
                  Imagine a dataset having 1000 rows, in this approach each row is considered as one cluster and closest point /cluster is measured at each step till we are left
                  with only one cluster.
2. Divisive :     Top--->Down approach
                  Imagine a dataset having 1000 rows, in this approach we start with only one cluster and reach to 1000 clusters at final step.
* Dendrograms are used to truncate at optimal number of clusters.
Clustering by Partitioning
K Means Clustering: A widely used clustering algorithm where we can consider k clusters at beginning
                    STEPS: Specify value of k
                           Partitioning of data into k clusters
                           Assign each record to cluster with new centroid
                           Recalculate for loosing and receiving clusters
                           When reassignment stops
                           Finalize the clusters
