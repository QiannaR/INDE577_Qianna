# Random Forest #

## 1. Introduction ##
Random Forest Classifier :
It is an ensemble tree-based learning algorithm. The Random Forest Classifier is a set of decision trees from randomly selected subset of training set. It aggregates the votes from different decision trees to decide the final class of the test object.



![Unknown](https://user-images.githubusercontent.com/98185045/167270136-0efe9ed0-9edb-4c1a-bfa9-9864a0ab547c.png)

## Advantages of random forest ##
1. It is one of the most accurate learning algorithms available. For many data sets, it produces a highly accurate classifier.
2. It runs efficiently on large databases.
3. It can handle thousands of input variables without variable deletion.

## Disadvantages of random forest ##
1. Random forests have been observed to overfit for some datasets with noisy classification/regression tasks.
2. For data including categorical variables with different number of levels, random forests are biased in favor of those attributes with more levels. Therefore, the variable importance scores from random forest are not reliable for this type of data.


## What I will do ##

I will use car evaluation dataset to do the random forest to see how the model predicts whether a car is acceptable or not.
## Libraries ##

[matplotlib] (https://matplotlib.org/)
[pandas] (https://pandas.pydata.org/)
[numpy] (https://numpy.org/)
[seaborn] (https://seaborn.pydata.org/)
[scikit-learn] (https://scikit-learn.org/) ...
