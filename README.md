# ARTI308 – Lab 4: Data Quality Assessment & Preprocessing

## Overview
This lab focuses on data preprocessing techniques using the `games.csv` dataset.  
The project applies data quality assessment, missing value handling, outlier detection, normalization, and PCA to prepare the dataset for further analysis.

## Dataset
The dataset used in this lab is:

`games.csv`

The dataset contains video game-related information such as release date, price, and Metacritic score.

## Objectives
- Load and explore the dataset
- Check and correct data types
- Detect and handle missing values
- Identify and remove outliers
- Apply normalization techniques
- Use PCA for dimensionality reduction and visualization

## Steps Performed

### 1. Data Loading
Loaded the dataset using Pandas and displayed the first rows to understand the data structure.

### 2. Data Quality Assessment
Checked the data types of all columns and identified columns that required conversion, such as `Release date`, `Price`, and `Metacritic score`.

### 3. Data Type Conversion
Converted important columns into suitable formats:
- `Release date` to datetime
- `Price` to numeric
- `Metacritic score` to numeric

### 4. Handling Missing Values
Detected missing values in the dataset and demonstrated different handling strategies:
- Removing records with missing values
- Mean imputation
- Median imputation

### 5. Handling Outliers
Used a boxplot and the IQR method to detect outliers in the `Price` column.  
Outliers were removed to improve data quality.

### 6. Normalization
Applied scaling techniques to numerical features:
- Min-Max Scaling
- Z-Score Standardization

### 7. PCA
Applied Principal Component Analysis (PCA) on selected numerical features to analyze variance and project the data into principal components.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Results
The dataset was successfully cleaned and prepared for analysis.  
Missing values, incorrect data types, and outliers were handled, and normalization techniques were applied.  
PCA was also used to understand feature variance and visualize the transformed data.

## Conclusion
This lab demonstrated important data preprocessing steps that are necessary before applying machine learning models.  
By cleaning the data, handling missing values and outliers, scaling features, and applying PCA, the dataset became more suitable for analysis and future modeling tasks.
