# dimas-kmeans
Simple implementation of K-Means in Javascript
Usage:
-------------------------------------
getClusters(data)
-
data : The data for clusterization, should be array of vectors (arrays), 
numberOfClusters : Optional, the default is Root of the size of the data divided by two.


	var kmeans = require('dimas-kmeans')

	var data = [
		[1,2],
		[2,1],
		[10,11],
		[12,13]
	]

	var clusters = kmeans.getClusters(data);

The result should be:
Cluster 1
-----------------
[ [ 10, 11 ], [ 12, 13 ] ]

Cluster 2
-----------------
[ [ 1, 2 ], [ 2, 1 ] ]
