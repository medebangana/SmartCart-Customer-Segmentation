# SmartCart-Customer-Segmentation
## Project Overview

This project focuses on developing an intelligent customer segmentation system for SmartCart, an e-commerce platform, using unsupervised machine learning techniques.

The objective is to identify meaningful customer groups based on demographics, purchasing behaviour, spending patterns, and engagement indicators. These segments can help businesses develop personalized marketing strategies, improve customer engagement, and support customer retention.

## Dataset

Dataset: SmartCart Customer Dataset

Total Records: 2,240 customers

Total Attributes: 22

Data Categories: Demographics, purchasing behaviour, website activity, and campaign response.

## Technologies Used

Python

Pandas and NumPy

Matplotlib and Seaborn

Scikit-learn

PCA

K-Means Clustering

Agglomerative Hierarchical Clustering

## Project Workflow

### 1. Data Preprocessing

Handled missing values using median imputation.
Identified and treated outliers.
Removed irrelevant attributes.
Standardized categorical values.

### 2. Exploratory Data Analysis (EDA)

Analysed customer demographics and purchasing patterns.
Examined feature distributions and correlations.
Visualized relationships between customer attributes using pairplots and heatmaps.

### 3. Feature Engineering

Created additional features to capture customer behaviour:

Age, Customer Tenure, Total Spending, Total Number of Children

### 4. Data Transformation

Applied One-Hot Encoding to categorical variables.
Used StandardScaler for feature scaling.
Applied Principal Component Analysis (PCA) for dimensionality reduction and visualization.

### 5. Customer Clustering

Implemented and explored two clustering algorithms:
K-Means Clustering
Used the Elbow Method to analyse Within-Cluster Sum of Squares (WCSS).
Applied the Silhouette Score to evaluate cluster separation.
Used KneeLocator to identify the elbow point.
Agglomerative Hierarchical Clustering
Applied bottom-up hierarchical clustering.
Used Ward linkage to minimize within-cluster variance.
Visualized hierarchical relationships using a dendrogram.

### 6. Model Evaluation

Evaluated clustering performance using:
Silhouette Score

### 7. Cluster Analysis

Analysed the characteristics of the generated customer segments based on income, age, spending patterns, and engagement indicators to derive meaningful business insights.

## Conclusion

This project demonstrates how unsupervised machine learning can be used to discover hidden patterns in customer data and transform them into actionable business insights. By comparing K-Means and Agglomerative Hierarchical Clustering, the project explores different approaches to customer segmentation and data-driven marketing.
