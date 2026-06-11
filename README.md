# DecodeLabs-Internship
#Task 2
# Credit Card Fraud Detection Using Machine Learning

## Introduction

Credit card fraud has become a significant challenge for financial institutions due to the increasing volume of online transactions. The objective of this project is to develop a machine learning-based fraud detection system capable of identifying fraudulent transactions while minimizing false alarms.

Since fraud cases represent only a small fraction of total transactions, the dataset is highly imbalanced. This project addresses that issue using SMOTE (Synthetic Minority Oversampling Technique) and evaluates the effectiveness of different classification algorithms.

---

## Problem Statement

The goal of this project is to build a predictive model that can accurately distinguish between legitimate and fraudulent credit card transactions.

---

## Dataset

The project uses the Credit Card Fraud Detection dataset, which contains anonymized transaction records.

### Features

- Time
- Amount
- V1 to V28 (anonymized numerical features)
- Class (Target Variable)

### Target Variable

- 0 = Legitimate Transaction
- 1 = Fraudulent Transaction

---

## Methodology

### Data Exploration

The dataset was examined to understand its structure and characteristics. This included:

- Checking dataset dimensions
- Reviewing data types
- Identifying missing values
- Detecting duplicate records
- Analyzing class distribution

### Exploratory Data Analysis

Several visualizations were created to gain insights into the data:

- Fraud vs Non-Fraud transaction distribution
- Transaction amount analysis
- Correlation heatmap
- Feature distribution plots

### Data Preprocessing

The following preprocessing steps were performed:

- Removal of duplicate records
- Feature scaling where required
- Train-test data splitting
- Handling class imbalance using SMOTE

### Model Development

Two machine learning models were implemented:

1. Logistic Regression
2. Random Forest Classifier

### Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## Results

The models were able to successfully identify fraudulent transactions.

### Logistic Regression

- ROC-AUC Score: 0.9765
- Strong recall performance for fraud detection

### Random Forest Classifier

- Improved classification performance
- Better ability to identify fraudulent transactions

The results demonstrate that machine learning techniques can effectively assist in detecting fraudulent financial activities.

---

## Conclusion

This project successfully developed a fraud detection system capable of identifying suspicious transactions with high accuracy. The use of SMOTE helped address the issue of class imbalance and improved the model's ability to detect fraudulent cases.

---

## Future Scope

Possible improvements include:

- Implementation of XGBoost and LightGBM models
- Hyperparameter optimization
- Real-time fraud detection systems
- Deployment through Flask or Streamlit

---
#Task 3
# Customer Segmentation Using Machine Learning

## Introduction

Understanding customer behavior is essential for businesses aiming to improve customer satisfaction and marketing effectiveness. Customer segmentation helps organizations divide customers into meaningful groups based on their characteristics and purchasing behavior.

This project applies machine learning techniques to identify customer segments and generate insights that can support targeted marketing strategies.

---

## Problem Statement

The objective of this project is to group customers into distinct segments based on demographic information, purchasing behavior, and spending patterns.

---

## Dataset

The project uses the Customer Personality Analysis dataset.

### Features Included

- Income
- Education
- Marital Status
- Age
- Product Spending
- Campaign Responses
- Purchase Frequency

---

## Methodology

### Data Understanding

The dataset was first examined to understand:

- Number of records and features
- Data types
- Missing values
- Duplicate records

### Data Cleaning

The following cleaning operations were performed:

- Handling missing values
- Removing duplicate records
- Correcting inconsistent data

### Feature Engineering

New variables were created to improve analysis, including:

- Age
- Total Spending
- Total Children
- Customer Tenure

### Exploratory Data Analysis

Several visualizations were used to explore customer behavior:

- Histograms
- Boxplots
- Correlation Heatmap
- Income Distribution
- Spending Analysis
- Purchase Pattern Analysis

### Data Preprocessing

Before clustering, the dataset was prepared using:

- Label Encoding
- Feature Scaling with StandardScaler

### Dimensionality Reduction

Principal Component Analysis (PCA) was applied to reduce dimensionality and improve visualization of customer segments.

### Clustering

K-Means Clustering was used to identify customer groups.

To determine the optimal number of clusters, the following methods were used:

- Elbow Method
- Silhouette Score

---

## Results

The clustering algorithm successfully identified meaningful customer segments.

Examples of customer groups include:

- High Income – High Spending Customers
- High Income – Low Spending Customers
- Moderate Income Customers
- Budget-Conscious Customers

These insights can help businesses design personalized marketing campaigns and improve customer engagement.

---

## Conclusion

The project demonstrates how machine learning can be used to uncover hidden patterns in customer data. The identified segments provide valuable information that can support business decision-making and customer relationship management.

---

## Future Scope

Potential improvements include:

- Hierarchical Clustering
- DBSCAN Clustering
- Real-time customer segmentation
- Interactive dashboards using Power BI or Tableau
- Integration with recommendation systems

---

## Author

Sahil Rawat 
