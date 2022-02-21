# GraphBasedConnectivityClustering

This is a Mathematica implementation of the clustering algorithm based on graph connectivity by: Li, Y.-F., Lu, L.-H., & Hung, Y.-C. A New Clustering Algorithm Based on Graph Connectivity. 2019, in Intelligent Computing, ed. K. Arai,S. Kapoor, & R. Bhatia (Cham: Springer International Publishing), 442–454.

It contains a function, connClustering, whose arguments are: the data (points), the size k of the neighbourhood used in constructing the kNN graph, the distances d and a, and an optional string argument ("yes"/"no") controling whether the results should be automatically saved to a file with the names k_d_a.txt and k_d_a.png (default is "no"). 

The notebook contains a simple three-cluster data set (1000 points) generated from a mixture of Gaussian distributions, which is fed to the function connClustering with k=6, d=5, a=7. Also a function for plotting the partitions from the output file k_d_a.txt is provided.

For convenience, the output file and plot are also made available.

This code was written in Mathematica v12.0.

If you use these implementations, please cite the corresponding paper:

M. Tarnopolski, Graph-based clustering of gamma-ray bursts, Astronomy and Astrophysics, 657, A13 (2022); https://arxiv.org/abs/2109.13204

Bibtex entry:

@ARTICLE{2022A&A...657A..13T,
       author = {{Tarnopolski}, Mariusz},
        title = "{Graph-based clustering of gamma-ray bursts}",
      journal = {Astronomy and Astrophysics},
     keywords = {gamma-ray burst: general, methods: data analysis, methods: statistical, Astrophysics - High Energy Astrophysical Phenomena, Astrophysics - Instrumentation and Methods for Astrophysics, High Energy Physics - Phenomenology},
         year = 2022,
        month = jan,
       volume = {657},
          eid = {A13},
        pages = {A13},
          doi = {10.1051/0004-6361/202038645},
archivePrefix = {arXiv},
       eprint = {2109.13204},
 primaryClass = {astro-ph.HE},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2022A&A...657A..13T},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}

