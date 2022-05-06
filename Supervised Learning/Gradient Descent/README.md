# Gradient Descent #

## Introduction ##

Gradient Descent is a very generic optimization algorithm capable of finding optimal solutions to a wide range of problems. The general idea of Gradient Descent is to tweak parameters iteratively in order to minimize a cost function.Suppose you are lost in the mountains in a dense fog; you can only feel the slope of the ground below your feet. A good strategy to get to the bottom of the valley quickly is to go downhill in the direction of the steepest slope. This is exactly what Gradient Descent does: it measures the local gradient of the error function with regards to the parameter vector θ, and it goes in the direction of descending gradient. Once the gra‐ dient is zero, you have reached a minimum!
Concretely, you start by filling θ with random values (this is called random initializa‐ tion), and then you improve it gradually, taking one baby step at a time, each step attempting to decrease the cost function (e.g., the MSE), until the algorithm converges to a minimum 

<img width="412" alt="Screen Shot 2022-05-06 at 12 01 04 AM" src="https://user-images.githubusercontent.com/98185045/167070118-4fd1d5be-47b8-4ca3-ab99-67ad1f237874.png">

## Algorithm in Math ##

1. To implement Gradient Descent, we need to compute the gradient of the cost function with regards to each model parameter θj. It is like asking “what is the slope of the mountain under my feet if I face east?” and then asking the same question facing north (and so on for all other dimensions, if you can imagine a universe with more than three dimensions).

<img width="290" alt="Screen Shot 2022-05-06 at 12 04 36 AM" src="https://user-images.githubusercontent.com/98185045/167070334-399a1ee5-081a-49d6-b256-d6a25dd26b7e.png">

2. Once you have the gradient vector, which points uphill, just go in the opposite direc‐ tion to go downhill. This means subtracting ∇θMSE(θ) from θ. This is where the learning rate η comes into play:6 multiply the gradient vector by η to determine the size of the downhill step

<img width="276" alt="Screen Shot 2022-05-06 at 12 05 52 AM" src="https://user-images.githubusercontent.com/98185045/167070431-3565b7f9-3f89-4e96-9b4e-b768030a3a38.png">


## Libraries ##
   1. Matplotlib
   2. Numpy
   3. Seaborn 
 
 ## Reference ##
 Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition, by Aurélien Géron
