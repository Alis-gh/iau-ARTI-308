# ARTI308 – Lab 5: Feature Engineering (Classification)

## Overview
This lab focuses on applying feature engineering techniques to improve a machine learning classification model.  
The project uses the `talabat_enhanced_orders.csv` dataset to predict food delivery order status based on order and delivery-related features.

## Dataset
The dataset used in this lab is:

`talabat_enhanced_orders.csv`

The dataset contains food delivery order information, including order details, delivery conditions, and categorical features used to predict `Order_Status`.

## Objectives
- Apply feature engineering to improve model performance
- Create new useful features from existing data
- Analyze the effect of categorical feature reduction
- Reduce feature space while maintaining model accuracy
- Evaluate classification model performance

## Completed Tasks

### Task 1: Distance per Item Feature
Created a new feature called `distance_per_item` to measure logistical delivery efficiency.

### Task 2: Peak Hour Rule
Tested an alternative peak hour rule to capture broader high-demand delivery periods.

### Task 3: Categorical Reduction
Analyzed the impact of `top_k` categorical reduction on model accuracy.

### Task 4: Feature Selection
Applied `SelectFromModel` to reduce the feature space by 50% while maintaining approximately 85.2% accuracy.

## Tools and Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib

## Results
Feature engineering helped improve the dataset representation and supported better model performance.  
The feature selection process successfully reduced the number of features by 50% while keeping the accuracy close to 85.2%.

## Conclusion
This lab demonstrated the importance of feature engineering in classification tasks.  
By creating meaningful features, adjusting categorical variables, and applying feature selection, the model maintained strong performance while becoming more efficient.
