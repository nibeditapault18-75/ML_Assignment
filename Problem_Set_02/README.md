Problem Set 02: Bank Marketing Prediction

 Problem Statement:

The objective of this problem is to predict whether a bank customer will subscribe to a term deposit or not using the Bank Marketing Dataset.

The required algorithm for this problem is Logistic Regression.

Dataset:

The dataset contains 45,211 records with 16 input features and 1 target variable.

The target variable is:
- `yes` → Customer subscribed
- `no` → Customer did not subscribe

 Methodology:

The following steps were performed:

1. Loaded the Bank Marketing dataset.
2. Preprocessed the data.
3. Converted the target values into 0 and 1.
4. Split the dataset into training and testing data.
5. Scaled numerical features.
6. Encoded categorical features.
7. Applied Logistic Regression.
8. Evaluated the model performance.

Findings:

The model achieved a high overall accuracy of 90.12%.
The ROC-AUC score of 90.56% also shows that the model can distinguish between the two classes quite well.
However, the recall for customers who subscribed was relatively low (34.78%). Therefore, the model could be improved further to identify more potential subscribers.   

Results:

- Accuracy: **90.12%**
- Precision: **64.45%**
- Recall: **34.78%**
- F1-Score: **45.18%**
- ROC-AUC: **90.56%**

 Conclusion:

The Logistic Regression model achieved **90.12% accuracy** in predicting whether a customer would subscribe to a term deposit.

