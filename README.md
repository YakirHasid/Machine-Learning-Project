# Machine Learning Project
## Introduction
In this project we trained Binary Classifiers of the Logistic Regression and KNN type, 

Including measuring their performance on a given dataset,

And evaluating their expected performance on an unknown dataset at the time of training.

## What is a Binary Classifier
A binary classifier is a function: 𝑓:ℛ^D ⟼ {0,1} associated with each vector in the property space x∈ℛ^D.

Where D is the dimension of the feature space one of the two possible values y ∈ {1,0}.

![image](https://github.com/YakirHasid/Machine-Learning-Project/assets/120096653/b9be8a5f-ff2b-4768-88d3-ca2f7c936ccb)


We used this data set that contains characteristics of sonar signal returns from two types of bodies, rocky and metallic, and the labeling of
each sample represents the body type from which the signal was returned.

# Part A
## Q6-8 : Training a KNN Binary Classifier for classifying sonar signals
KNN-type classifier is probabilistic in nature and is based on the model:

![image](https://github.com/YakirHasid/Machine-Learning-Project/assets/120096653/94a5d054-ffd5-437f-9beb-279f3b96962e)

![image](https://github.com/YakirHasid/Machine-Learning-Project/assets/120096653/6e7a3272-b54d-4e71-92f8-e07f91d2fbe3)

We loaded the dataset and prepared it for training,

Afterwards, we implemented the KNN algorithm in order to train the classifier,

Finally, we evaluated the binary classifier using a changing variable K value.

# Part B
## Q9-11 : Training a Logistic Regression Binary Classifier for classifying sonar signals
Logisitc Regression classifier is probabilistic in nature and is based on the model:

![image](https://github.com/YakirHasid/Machine-Learning-Project/assets/120096653/1f9cedb9-d948-43f2-a16f-14a7fcf832a4)

We implemented the Gradient Descent algorithm,

Afterwards, we trained the classifier and evaluated its performance along the training.

Finally, we discussed about the importance of the parameters of a binary classifier and how it affects on the algorithm results and on the classifier performance.

# Part C
## Q12 : The effect of the normalization of the characteristics on the performance of the algorithms
We normalized the dataset and repeated the experiment.

Afterwards, we compared the results of a normalized dataset vs. non-normalized dataset.

We found out that a normalized dataset has improved results.
