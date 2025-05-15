# credit_risk_classification
 ## Overview of the Analysis
The goal of this analysis was to build a predictive model using logistic regression to determine whether a loan applicant poses a high risk (1) or is a healthy loan (0). The financial dataset contained various features such as:

* loan_size

* interest_rate

*  borrower_income

* debt_to_income

* num_of_accounts

* derogatory_marks

* total_debt

**The target variable, loan_status, was a binary classification:**

* 0: healthy loan

* 1: high-risk loan

 **We performed the following steps:**

* Loaded and explored the dataset.

* Split the data into features (X) and target (y).

* Performed a train-test split using train_test_split().

* Trained a Logistic Regression model using the training data.

* Made predictions using the test set.

* Evaluated the model with a confusion matrix and a classification report.

## Results
# Logistic Regression Model:

* Accuracy Score: ~93%

* Precision (0 - healthy loans): High (e.g., 0.99)

* Recall (0 - healthy loans): High (e.g., 1.00)

* Precision (1 - high-risk loans): Low (e.g., 0.75)

* Recall (1 - high-risk loans): Very Low (e.g., 0.03)

## Summary
The logistic regression model demonstrates high accuracy and excellent performance for predicting healthy loans (class 0). However, its recall score for high-risk loans (class 1) is very low, meaning it fails to identify the majority of high-risk applicants.

This is likely due to class imbalance in the dataset, where healthy loans significantly outnumber high-risk loans.