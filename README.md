# K-Means-Clustering

Clustering is the process of dividing the entire data into groups (also known as clusters) based on the patterns in the data.
K-means is a centroid-based algorithm, or a distance-based algorithm, where we calculate the distances to assign a point to a cluster. In K-Means, each cluster is associated with a centroid.

The main objective of the K-Means algorithm is to minimize the sum of distances between the points and their respective cluster centroid.

Let’s now take an example to understand how K-Means actually works:

## Step 1:      
              Choose the number of clusters k
             The first step in k-means is to pick the number of clusters, k.
             

## Step 2:     
            Select k random points from the data as centroids
            Next, we randomly select the centroid for each cluster. Let’s say we want to have 2 clusters, so k is equal to 2 here. We then randomly select the centroid:

 
## Step 3:      
            Assign all the points to the closest cluster centroid
            Once we have initialized the centroids, we assign each point to the closest cluster centroid:

## Step 4:      
            Recompute the centroids of newly formed clusters
            Now, once we have assigned all of the points to either cluster, the next step is to compute the centroids of newly formed clusters:

## Step 5:     
          Repeat steps 3 and 4
          We then repeat steps 3 and 4:
          
## Stopping Criteria for K-Means Clustering

There are essentially three stopping criteria that can be adopted to stop the K-means algorithm:

1. Centroids of newly formed clusters do not change

2. Points remain in the same cluster

3. Maximum number of iterations are reached
