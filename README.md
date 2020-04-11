# GraphBasedConnectivityClustering

This is a Mathematica implementation of the clustering algorithm based on graph connectivity by: Li, Y.-F., Lu, L.-H., & Hung, Y.-C. A New Clustering Algorithm Based on Graph Connectivity. 2019, in Intelligent Computing, ed. K. Arai,S. Kapoor, & R. Bhatia (Cham: Springer International Publishing), 442–454.

This code was written in Mathematica v12.0.

It contains a function, connClustering, whose arguments are: the data (points), the size k of the neighbourhood used in constructing the kNN graph, the distances d and a, and an optional string argument ("yes"/"no") controling whether the results should be automatically saved to a file with the names k_d_a.txt and k_d_a.png (default is "no"). 

It contains a simple three-cluster data set (1000 points) generated from a mixture of Gaussian distributions, which is fed to the function connClustering with k=6, d=5, a=7. Also a function for plotting the partitions from the output file k_d_a.txt is provided.

For convenience, the output file and plot are also available.
