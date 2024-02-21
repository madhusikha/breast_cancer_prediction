# Breast_cancer_prediction

The goal of this project is to predict whether a patient has breast cancer or not, i.e., malignant or benign. To achieve this, ML models are built by training using Wisconsin dataset.

Brief Summary:

Wisconsin Dataset:
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

Details about the Dataset:
Number of features-33
Number of samples-569

Null values treatment:
One feature has all null values, so removed it.

'id' feature is unnecessary for model building, hence it is removed.

Used 70% of the data for Training and 30% for Testing all the models.

Results:
Mostly Logistic Regression (with different variations) is used for predicting the target and Adaboost model as shown below:

![Alt text](https://github.com/madhusikha/breast_cancer_prediction/blob/main/results.png)

Conclusion:
Logistic Regression with different variants were experiemented to find whether a patient belongs to benign or malignant.
It can be observed that when input data is transformed using PCA (30 features down to 6) and given as input to Logistic Regression and fine-tuned for different combinations of hyper-parameters, an accuracy of 98.8% and R2 score of 0.95 are achieved.
