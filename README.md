# ACM Research Coding Challenge (Fall 2020)


In order to obtain the optimal amount of clusters, I implemented the elbow method. 
To first prepare the data for being analyzed, it has to be normalized so that the upper representation of the values do not have a higher influence over the remaining values. Next I declared a range appropiate to the dataset (1-15) for the k values which equates to the number of centroids. Then the residential sum of squares is calculated for each k value utilizing a for loop and inertia. The graph is then displayed visualizing the comparison of RSS values and is ready to be analyzed. To read the optimal value of k, the elbow of the graph needs to be found. This can easily be observed as the point where the RSS value starts to stabilize. 
