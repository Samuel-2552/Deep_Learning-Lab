# Deep_Learning-Lab
All the Deep Learning Experiments

# What is Deep Learning?
Deep learning is a specific subfield of machine learning: a new take on learning representations from data that puts an emphasis on learning successive layers of increasingly meaningful representations.
The “deep” in “deep learning” isn’t a reference to any kind of deeper understanding achieved by the approach; 
rather, it stands for this idea of successive layers of representations. 
How many layers contribute to a model of the data is called the depth of the model. 
Other appropriate names for the field could have been layered representations learning or hierarchical representations learning.
Modern deep learning often involves tens or even hundreds of successive layers of representations, and they’re all learned automatically from exposure to training data. 
Meanwhile, other approaches to machine learning tend to focus on learning only one or two layers of representations of the data hence, they’re sometimes called shallow learning.
 In deep learning, these layered representations are learned via models called neural networks, structured in literal layers stacked on top of each other.
 
 For Example: A deep neural network for digit classification.
 ![image](https://user-images.githubusercontent.com/104893913/182282340-6a9d11ec-f2ef-4c4c-bf39-f0ce0f82112c.png)

A more detailed view:
![image](https://user-images.githubusercontent.com/104893913/182282493-7a627d9d-6e8c-462b-92dc-d4330396ebec.png)

Understanding how deep learning works:
1.) A neural network is parametrized by its weight.
![image](https://user-images.githubusercontent.com/104893913/182282798-7a93eba3-384e-41d8-9866-83879780a050.png)
2.) A loss function measures the quality of network's output
![image](https://user-images.githubusercontent.com/104893913/182282887-46902d0b-3767-43b6-81e9-edf5cfe1f889.png)
3.) The loss score is used as signal to adjust weights
![image](https://user-images.githubusercontent.com/104893913/182282963-e336ecf0-dfca-479f-a7f1-3e5700d3fe65.png)

# What is Correlation?

Variables within a dataset can be related for lots of reasons.

For example:

One variable could cause or depend on the values of another variable.
One variable could be lightly associated with another variable.
Two variables could depend on a third unknown variable.
It can be useful in data analysis and modeling to better understand the relationships between variables. The statistical relationship between two variables is referred to as their correlation.

A correlation could be positive, meaning both variables move in the same direction, or negative, meaning that when one variable’s value increases, the other variables’ values decrease. Correlation can also be neutral or zero, meaning that the variables are unrelated.

Positive Correlation: both variables change in the same direction.
Neutral Correlation: No relationship in the change of the variables.
Negative Correlation: variables change in opposite directions.
The performance of some algorithms can deteriorate if two or more variables are tightly related, called multicollinearity. An example is linear regression, where one of the offending correlated variables should be removed in order to improve the skill of the model.

We may also be interested in the correlation between input variables with the output variable in order provide insight into which variables may or may not be relevant as input for developing a model.

The structure of the relationship may be known, e.g. it may be linear, or we may have no idea whether a relationship exists between two variables or what structure it may take. Depending what is known about the relationship and the distribution of the variables, different correlation scores can be calculated.

In this tutorial, we will look at one score for variables that have a Gaussian distribution and a linear relationship and another that does not assume a distribution and will report on any monotonic (increasing or decreasing) relationship.


What is Tensor Flow?

What is Keras?


What are the Keras Models?
Sequential and Functional.

What are the keras layers?

What are the keras application?
https://keras.io/api/applications/
Xception
VGG16
VGG19
Resnet50
InceptionV3
Inception resnetV2
Mobile net
dense net
NASNED 
mobile net v2 tk

What are the Libraries included in the tensor flow?
https://www.tensorflow.org/resources/libraries-extensions

Use of pandas, numpy, sci-kit learn, seaborn?


UCI Machine Learning Repository.
provides most of the dataset for classfication, regression etc.
https://archive.ics.uci.edu/ml/index.php

Towards Data Science & MAcjine Learning Mastery Sites for reference.
