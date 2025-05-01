This is my Project #2 for extra credit for our Data Science I class, using K Means & Agglomerative Clustering for a dataset of 167 countries.

I leveraged Principal Component Analysis in order to map the data to a two dimensional plane to enable visualization of the clustering with improved readability.

I iterated through 8 K-values, generating plots showing the data and the centroids (with the centroids retaining the shape and relative distance of the clusters despite not being at the center of each cluster, due to the eigenvectors being on a different scale than the datapoints).
I used a Dendogram and an Elbow plot to help visualize the process leading to reaching the optimal number of clusters of 4 (balancing Silhouette scores with the degree of meaningful visual clustering).

It is worth noting I submitted this extra credit despite being well above the threshold for an A already, wanting extra practice for unsupervised learning.
