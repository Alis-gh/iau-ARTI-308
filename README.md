# ARTI308 – Lab 11: Credit Card Customer Segmentation with K-Means

## Overview

This lab applies **K-Means Clustering** to segment credit card customers based on their financial behavior and spending patterns.  
The main goal is to discover hidden customer groups using **unsupervised learning** techniques.

Customer segmentation can help businesses better understand customer behavior and improve marketing, targeting, and financial decision-making strategies.

---

## Dataset

The dataset used in this lab is:

```text
CC_GENERAL.csv
```

It contains credit card customer information, including:

- Balance
- Purchases
- Credit limit
- Cash advance usage
- Payments
- Payment frequency
- Purchase frequency
- Tenure

---

## Objectives

The main objectives of this lab are to:

- Perform customer segmentation using **K-Means Clustering**
- Explore and understand the dataset
- Handle missing values
- Scale numerical features using **StandardScaler**
- Determine the optimal number of clusters
- Evaluate clustering performance
- Visualize customer segments using **PCA**

---

## Steps Performed

The following steps were completed in this lab:

1. **Data Exploration**
   - Loaded the dataset
   - Displayed dataset information
   - Checked statistical summaries
   - Identified missing values

2. **Data Preprocessing**
   - Removed unnecessary columns
   - Handled missing values
   - Prepared numerical features for clustering

3. **Feature Scaling**
   - Applied **StandardScaler** to normalize the data
   - Ensured all features contributed fairly to the clustering process

4. **Finding the Optimal Number of Clusters**
   - Used the **Elbow Method**
   - Evaluated different values of K
   - Compared cluster performance using **Silhouette Score**

5. **Model Training**
   - Applied the **K-Means** algorithm
   - Assigned each customer to a cluster

6. **Cluster Visualization**
   - Used **Principal Component Analysis (PCA)**
   - Reduced the dataset into two dimensions
   - Visualized the customer segments using scatter plots

---

## Libraries Used

The following Python libraries were used:

- **Pandas** – data loading and manipulation
- **NumPy** – numerical operations
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualizations
- **Scikit-learn** – scaling, clustering, PCA, and evaluation

---

## Results

The K-Means model successfully grouped customers into different segments based on their financial behavior.

The clusters were mainly influenced by:

- Spending behavior
- Credit usage
- Cash advance activity
- Balance patterns
- Payment behavior

These customer segments can help businesses:

- Improve customer targeting
- Build personalized marketing strategies
- Identify high-value customers
- Understand risky or low-activity customer groups

---

## Conclusion

In this lab, K-Means Clustering was used to segment credit card customers based on their financial and spending patterns.  
After preprocessing the data, scaling the features, and evaluating different cluster numbers, the model was able to identify meaningful customer groups.

Using PCA visualization made it easier to understand how customers were distributed across different clusters.
