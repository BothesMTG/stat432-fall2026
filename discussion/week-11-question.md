---
id: w11-wenhao7-ward-kmeans
title: "Ward Clustering vs. K-Means Partitions"
author: wenhao7
---

Ward hierarchical clustering and K-means are both closely related to within-cluster sum of squares. If we cut a Ward dendrogram to obtain \(K\) clusters, should we expect that partition to be the same as the K-means solution with \(K\) clusters?

If not, what feature of Ward's greedy, irreversible merging procedure prevents it from solving the same global optimization problem as K-means?
