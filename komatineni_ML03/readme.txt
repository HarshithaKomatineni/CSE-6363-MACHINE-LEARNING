                                                                K-MEANS CLUSTERING ALGORITHM


NAME: KOMATINENI HARSHITHA 
UTA STUDENT ID:1001968082

IMPLEMENTATION:

First, we import the NumPy library, followed by defining the KMeans Class that will contain the functions to implement the KMeans algorithm as follows:

Initialize k means with random centroids

--> For a given number of iterations (max_iter):
    
	--> Iterate through the sample points

	--> Find the mean closest to the sample point by calculating the euclidean distance of the sample point with each of the means
        
	--> Assign sample point to mean
        
      --> Update mean by shifting it to the average of the sample points in that cluster

Finally, label all the sample points in the same centroid cluster as the same class.

To test this algorithm, we load the iris dataset, and split it into X and y (class labels). We fit the KMeans algorithm on X after scaling it. 

We decide which true label corresponds to which predicted label by running a short code. We can see that the accuracy is 85.33%



HOW TO RUN THE CODE:

1)Open the ipynb file in jupyter notebook and run it .



