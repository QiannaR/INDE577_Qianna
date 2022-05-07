# K Nearest Neighbors #

## Introduction ##

In statistics, the k-nearest neighbors algorithm (k-NN) is a non-parametric supervised learning method first developed by Evelyn Fix and Joseph Hodges in 1951, and later expanded by Thomas Cover.[2] It is used for classification and regression. In both cases, the input consists of the k closest training examples in a data set. The output depends on whether k-NN is used for classification or regression.

k-NN is a type of classification where the function is only approximated locally and all computation is deferred until function evaluation. Since this algorithm relies on distance for classification, if the features represent different physical units or come in vastly different scales then normalizing the training data can improve its accuracy dramatically.

## Steps ##
1. For implementing any algorithm, we need dataset. So during the first step of KNN, we must load the training as well as test data.
2. Next, we need to choose the value of K i.e. the nearest data points. K can be any integer.
tep 
3. For each point in the test data do the following −

  3.1 − Calculate the distance between test data and each row of training data with the help of any of the method namely: Euclidean, Manhattan or Hamming     distance. The most commonly used method to calculate distance is Euclidean.

  3.2 − Now, based on the distance value, sort them in ascending order.

  3.3 − Next, it will choose the top K rows from the sorted array.

  3.4 − Now, it will assign a class to the test point based on most frequent class of these rows.
 4. End

![knn_algorithm](https://user-images.githubusercontent.com/98185045/167072306-c49c3aa8-9b25-47f9-9f25-05e818b892cf.jpg)

## What we will do ##

n this project, I will build a KNN model from scratch by using car evaluation dataset.
## Libriaries ##
1. Numpy
2. Matplotlib
3. pandas

## Reference ##

https://www.tutorialspoint.com/machine_learning_with_python/machine_learning_with_python_knn_algorithm_finding_nearest_neighbors.htm

