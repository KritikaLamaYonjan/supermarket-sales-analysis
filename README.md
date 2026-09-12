# Supermarket Sales Analysis

## Overview

This project analyzes supermarket transaction data using Python.

The project focuses on data cleaning, data quality checking, outlier detection, machine learning-based anomaly detection, feature engineering, and exploratory data analysis.

## Objectives

- Identify data quality issues
- Clean and standardize the dataset
- Detect statistical outliers
- Detect unusual transactions using machine learning
- Create useful features from date and time data
- Analyze customer and sales behavior
- Explore relationships between sales and profitability

## Machine Learning

Two unsupervised machine learning techniques were used for anomaly detection:

- Isolation Forest
- Local Outlier Factor (LOF)

## Feature Engineering

New features were created including:

- Day of Week
- Time Hour
- Time of Day
- Refill Urgency Score
- Stock Refill Priority

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
supermarket-sales-analysis/
│
├── Supermarket_Sales_Analysis.ipynb
├── SuperMarket Analysis.csv
├── README.md
├── requirements.txt
└── .gitignore