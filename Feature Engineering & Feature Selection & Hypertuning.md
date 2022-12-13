![image](https://user-images.githubusercontent.com/106495355/207167112-baa22b6b-c40c-4161-8209-55ce9c1a7017.png)

![image](https://user-images.githubusercontent.com/106495355/207189437-17bcf04e-b6cc-407c-b9cf-f97485e3bd99.png)

# Feature Engineering
## Feature Engineering : creating new features to allow machine learning algorithms work better
### Applied machine learning is basically feature engineering. ---Andrew Ng
### Feature Transformations
1. Imputation: mean, median, most freq, multiple,...
2. Scaling: Log, standardize, minmax, BoxCox, YeoJohnson,...
3. Discretization/ Bining
4. Encoding: OHE, ordinal, target,...
5. Non-linear transformation: 1/x, x^2,|X|,x^2,sin(x),...
6. Linear and non-linear combinations
7. Cardinality reduction
8. Dimensinoality Reduction: PCA, SVD, MDS, NMD, Factor Analysis,...
9. Aggregations
10. Splines
11. Clustering
12. Embeddings
13. Dates/times
14. Times Series: Peaks, mean, max ,min, entropy,
15. Text: BOW, topic models, word2vec, embeddings
16. Images/Video: Edges, interest points, corners,...

### Awesome Tools
Python
1. sklearn.preprocessing
2. category_encoders
3. Featuretools
4. autofeat
5. dirty_cat
6. MIxtend

### Missing Data
1. Missing not at random (MNAR) : value is missing because of the true value itself
2. Missing at random (MAR): missing due to a value of another feature
3. Missing completely at random (MCAR): no pattern in when the value is missing

### Solutions:
1. Manually fix missing values
2. Use algo that are robust to missing data (XGBoost, LGBM, CatBoost)
3. Delete features and/or instances with missing values
4. Simple Imputation
5. Multiple Imputation

![image](https://user-images.githubusercontent.com/106495355/207169322-528fe3e2-b7f8-4aaf-9efc-1a8da2ca74ab.png)

![image](https://user-images.githubusercontent.com/106495355/207169719-a4b19bdd-1ede-48b9-9291-45b158b18455.png)

![image](https://user-images.githubusercontent.com/106495355/207169869-56deb750-067e-4759-8226-e910901573f8.png)

![image](https://user-images.githubusercontent.com/106495355/207169928-153d1357-158c-4ec2-81a4-c125d3e2b858.png)

![image](https://user-images.githubusercontent.com/106495355/207169972-9e459165-28c6-4cc4-b75d-4d67bf335e8c.png)

### Encoding
1. One hot encoding/Dummy coding/Effect coding
2. Ordinal encoding
3. Contrast encoding
4. Hashing

![image](https://user-images.githubusercontent.com/106495355/207170420-6a732e63-66f1-491f-8b57-72e965840180.png)

![image](https://user-images.githubusercontent.com/106495355/207170558-78430d49-5c81-4957-84eb-fbe09bd775e0.png)


# Feature Selection
## Feature Selection: Process of selecting a subset of features to use in model training
### Two Methods
1. Filter Methods: use stats to remove bad/useless features before model training

![image](https://user-images.githubusercontent.com/106495355/207171056-5713ed6a-3e9c-40b5-84e2-1b65e12a8ca2.png)

2. Wrapper Methods (stepwise selection): find the best subsets of features by training and evaluating models on many subsets of features 

![image](https://user-images.githubusercontent.com/106495355/207171487-a9eebdc3-5e99-4a20-a4fd-e3698c57e7ea.png)


# Hyperparameter Tuning
### Hyperparameter Tuning: Choosing the best values for hyperparameters

![image](https://user-images.githubusercontent.com/106495355/207183000-6e2fa4fb-d224-43f0-8460-d8a7b7739535.png)

### Grid Search
1. max depth: 5,10,15,20,...
2. Impurity metric: info gain,gini, variance reduction
3. Min sampels: 1,10,25,50,100

![image](https://user-images.githubusercontent.com/106495355/207183348-ee3c1221-d09c-4524-9719-7482e08aa8f1.png)

### Random Search
1. Max depth:[5,35]
2. Impurity metric: [info gain, gini, variance reduction]
3. Min samples: [1-100]

![image](https://user-images.githubusercontent.com/106495355/207183492-c2fd02a0-3d4b-417d-aaba-3bf383c03a30.png)

### Advanced Search Algorithms
![image](https://user-images.githubusercontent.com/106495355/207183598-295bf45f-96dc-4b27-8176-2f2720baa24b.png)

![image](https://user-images.githubusercontent.com/106495355/207183693-e97b90ff-fa65-4763-a29d-a47bfa4c6cc8.png)











