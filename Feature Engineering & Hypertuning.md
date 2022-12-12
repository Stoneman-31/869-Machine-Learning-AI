![image](https://user-images.githubusercontent.com/106495355/207167112-baa22b6b-c40c-4161-8209-55ce9c1a7017.png)

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






