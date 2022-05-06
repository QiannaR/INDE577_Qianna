# Principal Component Analysis #

## 1. Introduction ##

rincipal Component Analysis (PCA) is by far the most popular dimensionality reduc‐ tion algorithm. First it identifies the hyperplane that lies closest to the data, and then it projects the data onto it.
PCA identifies the axis that accounts for the largest amount of variance in the train‐ ing set. In Figure 8-7, it is the solid line. It also finds a second axis, orthogonal to the first one, that accounts for the largest amount of remaining variance. In this 2D example there is no choice: it is the dotted line. If it were a higher-dimensional data‐ set, PCA would also find a third axis, orthogonal to both previous axes, and a fourth, a fifth, and so on—as many axes as the number of dimensions in the dataset.

## 2. SVD ##

how can you find the principal components of a training set? Luckily, there is a standard matrix factorization technique called Singular Value Decomposition (SVD) that can decompose the training set matrix X into the matrix multiplication of three matrices U Σ VT, where V contains all the principal components that we are looking for, as shown in

<img width="225" alt="Screen Shot 2022-05-06 at 1 13 21 AM" src="https://user-images.githubusercontent.com/98185045/167076988-f3e1a001-1118-4b55-8361-77a76ac2ddaf.png">

## Reference ##3

Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition, by Aurélien Géron
