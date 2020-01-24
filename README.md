# K-MeansClusteringAlgorithm
This is basic implementation of K-Means Clustering algorithom. K-Means clustering allowed us to approach a domain without really knowing a whole lot about it, and draw conclusions and even design a useful application around it.
The algorithm will categorize the items into k groups of similarity. To calculate that similarity, we will use the euclidean distance as measurement.
The algorithm works as follows:

First we initialize k points, called means, randomly.
We categorize each item to its closest mean and we update the mean’s coordinates, which are the averages of the items categorized in that mean so far.
We repeat the process for a given number of iterations and at the end, we have our clusters.
