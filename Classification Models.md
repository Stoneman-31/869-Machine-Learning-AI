# Classification

## Business Applications

![image](https://user-images.githubusercontent.com/106495355/206822112-5ba6d567-30ef-46c7-a9c7-9fcb6af3e1de.png)

## Popular Classification Algorithms

![image](https://user-images.githubusercontent.com/106495355/206822155-122d6419-1e24-4340-8afe-a3127d33a07c.png)

## Python Packages

![image](https://user-images.githubusercontent.com/106495355/206822188-781766b4-f260-4409-821e-5989494365b2.png)

## Which One is the Best?

![image](https://user-images.githubusercontent.com/106495355/206822256-41fe71d9-5266-4025-a063-81f26a16e996.png)

## Hyperparameters
### The settings that control the algorithm's behaviour

# Model Theories

## Decision Trees
### TrainingL the algorithm builds a tree with rules
### Model: the tree itself
### Prediction: answer questions at each node until you reach a leaf

![image](https://user-images.githubusercontent.com/106495355/206822476-7e241707-7953-463c-a81c-4d106ed18541.png)
### At Training Phases, algo finds best feature for root node
    Algo computes entropy of target
    Algo computes info gain of each feature
    Algo selects features with highest info gain
    *Entropy* = a measure to determine how mixed the target is. 
    Target mostly different -> High entropy
    Target mostly the same -> Low entropy
![image](https://user-images.githubusercontent.com/106495355/206822913-1d8deedf-105a-4a25-8e73-66bf4b3c2f4b.png)

### Stopping Conditions
    All instances belong to the same target (i.e., entropy =0.0)
    *min_sample_split* hyperparameter reached. 
    *max_depth* hyperparameter reached. 

## Summary Decision Tree
### Pros:
Fast and Efficient
Easy to understand the model, can be visualized
little data prep requried: Can handle nonlinear data and feature interactions

### Cons:
Good, not great at predictive performance

![image](https://user-images.githubusercontent.com/106495355/206824081-76a28fbf-bf36-4ddb-9085-ee1680a84704.png)


## Naive Bayes
### Training: Calculates distributions per feature/class
### Model: the distributions
### Prediction: calculates probability of each class; choose largest

### Pros: 
Fast and Efficient
Interpretable
Resistant to overfitting

### Cons:
Makes a strong assumption: features are independent
Performance not great

![image](https://user-images.githubusercontent.com/106495355/206824432-3a92aafb-5340-492d-9bc8-d8dcd3bd69e3.png)

## K Nearest Neighbours (KNN)
### Training: None
### Model: None
### Prediction: Find the K nearest instances in the training data; majority wins

### Pros:
Easy to understand, implement, and interpret
Training is very fast
Usualy not bad

### Cons:
Memory intensive
Prediction can be slow

![image](https://user-images.githubusercontent.com/106495355/206824545-4ab77a9d-a2ad-4003-8c5a-9aac9cd7335f.png)

## Support Vector Machines (SVM)
###  Main idea: draw a straight line to separate the classes as much as possible
###  Training: Algo tries a bounch of lines, choose best
###  Model: Equation of the line
###  Prediction: Determine which side of the line
###  SVM uses the *kernel trick* to create non-linear decision boundary

![image](https://user-images.githubusercontent.com/106495355/206825568-a42af0f5-049a-4187-94f2-b5d99bdf5991.png)

