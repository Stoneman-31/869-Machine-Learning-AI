# Performance Metrics
## Regression
1. Mean Squared Error
2. Mean Absolute Error
3. Root MSE

## Classification
1. Accuracy/Error
2. Precision, Recall
3. F1 Score
4. Sensitivity, Specificity
5. ROC Curve and AUC
6. Log Loss

## Recommendation
1. Mean Average Precision @ K
2. Coverage
3. Personalization
4. Intra-list similarityvv

## Confusion Matrix : a tabulation of the predictions against the truth
1. True Positive 2. True Negative 3. False Positive 4. False Negative

![image](https://user-images.githubusercontent.com/106495355/207141004-debca91c-eeda-4a00-9612-f00f7898f03b.png)

### Accuracy: Percentage of instances that are classified correctly
1 - Accuracy = Error

Accuracy = (TP+TN)/(TP+TN+FP+FN)

Accuracy is a bad measurement because it only tells how right the deicions are but nothing about the wrong part. Sometimes, we prefer false postive over false negative or vise versa. Accuracy cannot tell us about that. 

### Precision : % of "yes" predicitons that are correct
Precision = TP/(TP+FP)

### Recall : % of truth "yes" were correctly predicted as "yes"
Recall = TP/(TP+FN)

### F1 Score : Harmonic mean between precision and recall
F1 = (2* Precision * Recall) /(Precision + Recall)

![image](https://user-images.githubusercontent.com/106495355/207140834-52a621f5-712e-47ff-88da-b34dfd706212.png)









