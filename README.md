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


