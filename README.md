Unsupervised learning is also known as
learning by observation in machine learning which
groups the data instances based on their similarities.
k-Means clustering technique is one of the most
commonly used partition-based clustering methods
that continuously relocate data instances from one
cluster to another cluster to ameliorate the cluster
validation. In this paper, we have introduced a new
approach to improve the data clustering performance
of the k-Means clustering algorithm. The proposed
approach significantly reduces the number of itera-
tions. Initially, we need to set the value of k, the
number of clusters, and randomly select k number
of instances from data as initial cluster centers. Then
rest of the instances are assigned to the clusters based
on the minimum Euclidean value. In the traditional
k-means clustering method, each data instance is
compared with each cluster center. But, in this pro-
posed method we assign an instance into a cluster
based on the average value of all instances that
are already assigned to the cluster instead of the
cluster center. The primary innovation lies in this
modification of the assignment of instances into a
cluster, which diverges significantly from conventional
methodologies. By harnessing the in-place-mean of
cluster instances calculation during assignments, the
proposed approach significantly curtails the number
of iterations required for convergence
