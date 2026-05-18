# ARTI308 – Lab 9: Decision Trees & Random Forest

## Overview
This lab focuses on predicting loan repayment status using supervised machine learning models.  
The project applies both Decision Tree and Random Forest classifiers to analyze financial data and evaluate their performance.

## Dataset
The dataset used in this lab is:

`loan_data.csv`

It contains financial and borrower-related information used to predict whether a borrower fully paid their loan or not.

## Objectives
- Preprocess the dataset before training
- Train a Decision Tree model
- Train a Random Forest model
- Evaluate and compare model performance
- Analyze prediction results

## Tools and Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib

## Models Used
- Decision Tree Classifier
- Random Forest Classifier

## Results

| Model | Accuracy | Notes |
|---|---:|---|
| Decision Tree | 73% | Performs better at identifying borrowers who did not fully pay |
| Random Forest | 85% | Achieves higher overall accuracy but misses most defaulters |

## Conclusion
The Random Forest model achieved the highest accuracy overall, making it the stronger model in terms of general prediction performance.  
However, the Decision Tree model showed better performance in detecting borrowers who did not fully repay their loans, which is important in loan risk prediction tasks.
