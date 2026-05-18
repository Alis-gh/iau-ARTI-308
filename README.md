# ARTI308 – Lab 3: Exploratory Data Analysis (EDA)

## Overview
This lab focuses on performing Exploratory Data Analysis (EDA) on the Steam Games dataset.  
The project analyzes the dataset to understand its structure, identify missing values, check duplicates, and explore relationships between numerical features.

## Dataset
The dataset used in this lab is:

`games.csv`

The dataset contains information about Steam games, including price, Metacritic score, positive reviews, and negative reviews.

## Objectives
- Load and explore the dataset
- Check missing values
- Check duplicate rows
- View dataset shape and data types
- Generate statistical summaries
- Analyze feature distributions
- Explore relationships between numerical variables
- Visualize correlations between features

## Steps Performed

### 1. Import Libraries
Imported the required Python libraries for data analysis and visualization.

### 2. Load Dataset
Loaded the `games.csv` dataset using Pandas and displayed the first rows.

### 3. Data Quality Check
Checked the dataset for:
- Missing values
- Duplicate rows
- Number of rows and columns
- Column data types

### 4. Statistical Summary
Generated descriptive statistics to understand the numerical features in the dataset.

### 5. Univariate Analysis
Analyzed the distribution of `Metacritic score` using a histogram.

### 6. Bivariate Analysis
Explored relationships between:
- Price and Metacritic score
- Positive and negative reviews

### 7. Correlation Analysis
Created a correlation matrix to show relationships between numerical features.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Results
The dataset was successfully explored and visualized.  
The analysis showed that most games have mid-range Metacritic scores.  
There was no strong relationship between game price and rating, while games with more positive reviews also tended to have more negative reviews.

## Conclusion
This lab demonstrated how Exploratory Data Analysis helps understand a dataset before applying machine learning techniques.  
By checking data quality, analyzing distributions, and visualizing relationships, the dataset became easier to interpret and prepare for future analysis.
