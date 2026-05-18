# ARTI308 – Lab 10: Support Vector Machines (SVM)

## Overview

This lab focuses on implementing **Support Vector Machines (SVM)** to classify the famous **Iris flower dataset**.  
The project includes data exploration, visualization, model training, model evaluation, and hyperparameter tuning using **GridSearchCV**.

## Dataset

The Iris dataset, also known as Fisher's Iris dataset, is a classic machine learning dataset introduced by **Sir Ronald Fisher in 1936**.

The dataset contains **150 samples** from three different Iris flower species:

- Iris setosa
- Iris versicolor
- Iris virginica

Each species contains **50 samples**.

## Features

Four numerical features were measured for each flower sample:

- Sepal length in cm
- Sepal width in cm
- Petal length in cm
- Petal width in cm

The target variable is the flower species.

## Project Workflow

### 1. Data Loading

The dataset was loaded using the Seaborn library:

```python
iris = sns.load_dataset('iris')
