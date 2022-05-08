## Decision Trees ##

A tree has many analogies in real life, and turns out that it has influenced a wide area of machine learning, covering both classification and regression. In decision analysis, a decision tree can be used to visually and explicitly represent decisions and decision making. As the name goes, it uses a tree-like model of decisions. 


![1*XMId5sJqPtm8-RIwVVz2tg](https://user-images.githubusercontent.com/98185045/166846038-51b4c3b6-2e59-4fc9-bbfd-587e694d3bf1.png)

A decision tree is drawn upside down with its root at the top. In the image on the left, the bold text in black represents a condition/internal node, based on which the tree splits into branches/ edges. The end of the branch that doesn’t split anymore is the decision/leaf, in this case, whether the passenger died or survived, represented as red and green text respectively.
Although, a real dataset will have a lot more features and this will just be a branch in a much bigger tree, but you can’t ignore the simplicity of this algorithm. The feature importance is clear and relations can be viewed easily. This methodology is more commonly known as learning decision tree from data and above tree is called Classification tree as the target is to classify passenger as survived or died. Regression trees are represented in the same manner, just they predict continuous values like price of a house.
 
 ## Tasks ##
 
 I will use car evaluation dataset to do the decision tree.

# DataSet #
 This Data is from Kaggle. It is a car evaluation dataset. This data set is composed of 1728 rows and 6 different attributes which are buying price, price of maintenance, number of doors, capacity in terms of persons to carry, the relative size of luggage boot and the estimated safety value of each car. There is no missing value in the data set as a big advantage  We can use this dataset to do prediction.
 
# Libraries #
  1. numpy
  2. matpltlib
  3. pandas
  4. seaborn
  5. Scikit-learn
