# Supervised-Machine-Learning-Challenge
Predicting Credit Risk

This challenge is to create machine learning models to classify the risk level of given loans, specifically, comparing the Logistic Regression model and Random Forest Classifier.

The following steps are performed to complete this challenge:
## 1)   Retrieve Data
The data used to build the models is retrieved from Resources/lending_data.csv

## 2)   Predict Model Performance
A prediction of which model will perform better (Logistic Regression or Random Forest Classifier) is made, before creating the models. 

## 3)   Split the Data into Training and Testing Sets
-   The features dataframe (X) is created by dropping the loan_status column.
-   The labels set (y) is created by using the loan_status column.
-   The training and testing datasets are created by splitting the data using the train_test_split function.

## 4)   Create, Fit and Compare Models
-   A Logistic Regression model is created and fit to the training data created above. The model's score is then determined by using the score function and the testing data from above.

-   Similarly, a Random Forest Classifier is created and fit to the training data created above. The model's score is then determined by using the score function and the testing data from above.

-   The scores for each model is reviewed and conclusions written.

## Files Uploaded
-   **Jupyter Notebook** - Credit Risk Evaluator.ipynb
-   **Input File** - Resources/lending_data.csv
