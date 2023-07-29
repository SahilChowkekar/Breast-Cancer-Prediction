# Breast-Cancer-Prediction-

This project aims to analyze the Breast Cancer Wisconsin Diagnostic Dataset using supervised and unsupervised machine learning
methods. The dataset contains information about breast cancer tumors, including numerical features that describe each tumor. We are
trying to solve two problem definitions. The problem definition is to cluster the tumors into groups based on their similarity. For the clustering problem, unsupervised
learning methods such as K-means clustering and Spectral Clustering will be used to group similar tumors together based on their
features. The performance of each clustering algorithm will be evaluated using metrics such as the Silhouette Coefficient scores and
the Normalized Mutual Information scores.

Overview:
Spectral clustering is a technique where the data points can
easily be distinguishable from the original data to transformed clusters. It is a method that outperforms K-means
clustering. Firstly, we constructed a similarity graph from
the original data points, in which the data points serve as
nodes and are connected by edges. The graph is then turned
into a Laplacian matrix and decomposed into eigenvalues
and eigenvectors. An eigenvector with modest eigenvalues
is utilized to generate data points in low-dimensional space.
Generally, the mapping is accomplished by the use of a few
eigenvectors that include the essential data points from the
original data. There are many benefits to the spectral clustering method. Firstly, they generally are capable of handling
data that cannot be separated linearly. This is due to the
fact that it works in a higher-dimensional area and can recognize intricate patterns and clusters. Secondly, network
analysis applications such as community discovery, finding
functional modules in biological networks, and other network analysis tasks can benefit from spectral clustering’s
ability to handle both graphs and networks. Lastly, it is a
soft clustering strategy, which implies that it gives each data
point for each cluster a chance of membership. In situations
when data points may be a part of numerous clusters, this is
helpful.
The algorithm of Spectral Clustering can be written as:
(1) Create a similarity graph.
(2) Calculate the Adjacency matrix Degree matrix and Laplacian matrix.
(3) Calculate the eigenvectors of the Laplacian matrix
(4) As an input, utilize a few of the lowest eigenvectors to
classify the data. Clustering is then carried out using the
data’s low-dimensional representation. Several clustering
techniques, such as k-means, can be used to do this.
