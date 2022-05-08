## K-Means Clustering ##

## 1. Introduction ##
The K-Means algorithm is a simple algorithm capable of clustering this kind of dataset very quickly and efficiently, often in just a few iterations. It was pro‐ posed by Stuart Lloyd at the Bell Labs in 1957 as a technique for pulse-code modula‐ tion, but it was only published outside of the company in 1982, in a paper titled “Least square quantization in PCM”.1 By then, in 1965, Edward W. Forgy had pub‐ lished virtually the same algorithm, so K-Means is sometimes referred to as Lloyd- Forgy.




![hqdefault](https://user-images.githubusercontent.com/98185045/167270575-cf34683d-3abf-4958-a792-bb8759222a1e.jpg)

## How does K means work ##


Suppose you were given the centroids: you could easily label all the instances in the dataset by assigning each of them to the cluster whose centroid is closest. Conversely, if you were given all the instance labels, you could easily locate all the centroids by computing the mean of the instances for each cluster. But you are given neither the labels nor the centroids, so how can you proceed? Well, just start by placing the centroids randomly (e.g., by picking k instances at random and using their locations as centroids). Then label the instances, update the centroids, label the instances, update the centroids, and so on until the centroids stop moving. The algorithm is guaranteed to converge in a finite number of steps (usually quite small).


## Task ##

I will implment the K means clustering algorithm to do the wholesale dataset.

## Data ##
This data is from UCI about the wholesale customer. The dataset refers to clients of a wholesale distributor. It includes the annual spending in monetary units (m.u.) on diverse product categories.

## Reference ##

 Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition, by Aurélien Géron
