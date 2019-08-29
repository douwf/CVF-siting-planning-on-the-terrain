# CVF-siting-planning-on-the-terrain
The code of CVF,RPF,SA algorithm are presented in the CODE.zip.
The DATA.zip includes dataset D1,D2 and D3.

The code of CVF algorithm  is in the CVF folder, in which Go.java is first executed to cluster and sort the terrain feature points, and then Delaunay_1000.java is  to filter the viewpoints for each cluster.
Compute.java uses the Reference plane algorithm to compute the viewshed of each viewpoint.
Extract.java is to extract the terrain feature points; K_cluster.java is to cluster these feature points and the Sort.java is to sort each cluster.

The code of RPF algorithm is in the myvoronoi folder of the RPF&SA folder,in which PartitionFilter_1000.java is to filter the viewpoints and Thiessen.java is to generate  thiessen polygon.

The code of SA algorithm is in the experiment1 folder of the RPF&SA folder,in which SA_1000.java is to perform SA algorithm.

The gdal folder is to read image data.
