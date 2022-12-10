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
    ~max_depth~ hyperparameter reached. 






