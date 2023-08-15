# Module 12 Report Template

## Overview of the Analysis

For the purpose of this analysis, the objective was to construct machine learning algorithms that can forecast the outcomes of loans based on diverse financial attributes. The dataset encompassed details regarding the magnitude of loan sizes, interest rates, borrower income, debt-to-income ratios, number of accounts, derogatory marks, and total debt.

The primary aim revolved around anticipating whether a loan would fall into the category of a sound loan (0) or a high-risk loan (1). The dataset's distribution was skewed, with a notably larger count of sound loans compared to high-risk loans.

Quantity of sound loans (0): 75,036
Quantity of high-risk loans (1): 2,500

The approach followed these phases within the machine learning pipeline:

Data Preprocessing: The dataset was divided into two segments, features(X) and labels (y). Subsequently, a further division was made into training and testing subsets through utilization of the train_test_split function.

Model Selection and Training: Opted for two distinct models for making predictions:
Model 1: Logistic Regression
Model 2: Random Forest model

Prediction and Evaluation: Employing the designated models, predictions were made concerning the loan statuses for the testing dataset. An assessment of their efficacy was carried out employing diverse metrics, which encompassed the balanced accuracy score, precision, recall, and the confusion matrix.

## Results

Machine Learning Model 1: Logistic Regression
  Balanced Accuracy Score: 0.9443
  Precision (healthy loans): 1.00
  Precision (high-risk loans): 0.87
  Recall (healthy loans): 1.00
  Recall (high-risk loans): 0.89

Machine Learning Model 2: Random Forest Model
  Balanced Accuracy Score: 0.9443
  Precision (healthy loans): 1.00
  Precision (high-risk loans): 0.88
  Recall (healthy loans): 1.00
  Recall (high-risk loans): 0.88

## Summary

Both Model 1, the Logistic Regression approach, and Model 2, the Random Forest technique, did a great job in guessing whether loans would be okay or risky. Surprisingly, both models got the same score of 0.9443 for accuracy, which means they were equally good at being careful with both safe and risky loans.

How good these models are depends on the particular situation we're looking at. In this case, the accuracy score tells us that both models worked well for figuring out if loans were safe or risky. This is important because it helps us make fair judgments about loans.

Since these models performed well, I suggest using either Model 1 (Logistic Regression) or Model 2 (Random Forest) for guessing about loan outcomes. They're both good at predicting both safe and risky loans. However, in terms of writing code, Model 1 (Logistic Regression) might be easier and quicker to use based on the results I got.