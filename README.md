# Customer Churn Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a
Telco Customer Churn dataset using Python.

The goal is to understand customer behavior and identify patterns
related to customer churn.

## 🎯 Objectives

This project covers:

1. First look at the dataset
2. Missing data analysis
3. Summary statistics
4. Duplicate detection
5. Distribution analysis
6. Correlation and relationships
7. Outlier detection
8. Categorical analysis
9. Customer churn / target analysis
10. Data quality checks

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Dataset

Dataset: Telco Customer Churn

Source:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## 🎯 Target Variable

The target variable is:

`Churn`

It indicates whether a customer left the company.

## 🔍 Analysis Performed

### 1. First Look
- `df.head()`
- `df.tail()`
- `df.shape`
- `df.info()`
- `df.columns`
- `df.dtypes`

### 2. Missing Data
- Missing value counts
- Missing value percentages
- Missing value visualization

### 3. Summary Statistics
- Numerical statistics
- Categorical statistics
- Frequency counts
- Unique values

### 4. Duplicate Analysis
- Detect duplicate rows
- Remove duplicate rows

### 5. Distribution Analysis
- Histograms
- Boxplots
- KDE plots
- Skewness
- Kurtosis

### 6. Correlation Analysis
- Correlation matrix
- Heatmap
- Pairwise relationships
- Scatterplots

### 7. Outlier Detection
- IQR method
- Z-score method
- Boxplots

### 8. Categorical Analysis
- GroupBy
- Aggregations
- Crosstab
- Countplots

### 9. Target Analysis
- Churn class distribution
- Churn percentage
- Feature vs Churn analysis

### 10. Data Quality
- Missing values
- Incorrect data types
- Inconsistent formatting
- Impossible values
- Duplicate records

## 📁 Project Structure

```text
customer_churn_analysis/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── customer-churn-analysis.ipynb
│
└── README.md
