## A Cost-Sensitive Neural Network for Identifying Poisonous Mushrooms

In traditional classification problems, all possible types of misclassification errors are assumed to carry the same cost. For example, in binary classification, a false negative is presumed to be just as costly of an error as a false positive. However, this is not the case in many problem contexts. For situations in which costs differ according to the type of misclassification made, cost-sensitive models are employed. One example in which such a model would be useful is the classification of edible and poisonous mushrooms. A cost-sensitive model would be useful in this context because misclassifying a poisonous mushroom as being edible is a much more egregious error than vice versa.

The Mushroom Dataset is obtained from the UC Irvine Machine Learning Repository. The dataset consists of 8,124 observations and 22 different mushroom features, such as cap shape, cap surface, habitat, and color. The binary class outcome variable is the edibility of the mushroom, where the classes include poisonous or edible. 

In the past, several others have implemented artificial neural networks and other data mining techniques such as decision trees on this mushroom data set with high success. In this project, I aim to build upon past work by building a cost-sensitive neural network to account for the varying misclassification costs. 


