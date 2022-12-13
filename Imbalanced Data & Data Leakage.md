# Imbalanced Data
### Imbalanced data : data sets in which there is a disproportionate ratio of instances in one target class. 

## Solutions

![image](https://user-images.githubusercontent.com/106495355/207184590-dba662ec-710f-414b-a83b-4aeed54e6df5.png)

### Class Weights
Tells algo to increase the cost of misclassifying the minority class
  clf =DecisionTreeClassifier(class_weight = "balanced")
Algo will adjust loss function appropriately
Simple and effective!

### Over Sample
Randomly duplicate instances from minority class

![image](https://user-images.githubusercontent.com/106495355/207184906-a7c06eee-56fc-44a4-a1f9-90ee0b16ef8e.png)

### Generate Synthetic Data
Similar to over sampling, but instead generates artificial data that is close to an instance in the minrity class. 
Common methods: SMOTE, ROSE, ADASYN

### Under Sample
Randomly remove instances from majority class

# Data Leakage
1. Target Leakage
2. Bad Splitting
3. FE before splitting
4. Duplicate instances
5. Groups

## Scalling before Splitting

![image](https://user-images.githubusercontent.com/106495355/207186168-e3a55ae7-1528-4fd5-8503-9aa9d2921538.png)
