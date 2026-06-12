# Fraud Detection Project

## Project Overview

This project focuses on fraud detection for e-commerce and bank credit card transactions. The goal is to prepare clean, feature-rich datasets and later build machine learning models that can identify fraudulent transactions.

## Business Problem

Fraud detection is important because false positives can affect customer trust, while false negatives can cause financial loss. This project aims to balance these risks using data analysis, feature engineering, and machine learning.

## Datasets

The project uses three datasets:

1. `Fraud_Data.csv` — e-commerce transaction data.
2. `IpAddress_to_Country.csv` — IP address to country mapping.
3. `creditcard.csv` — anonymized bank credit card transaction data.

## Interim 1 Progress

For Interim 1, the following tasks were completed:

- Data cleaning
- Missing value checking
- Duplicate removal
- Data type correction
- Exploratory data analysis
- Class imbalance analysis
- IP address to country mapping
- Time-based feature engineering
- Transaction frequency feature engineering
- Data transformation preparation
- SMOTE strategy explanation

## Project Structure

```text
fraud-detection/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── eda-fraud-data.ipynb
│   ├── eda-creditcard.ipynb
│   └── feature-engineering.ipynb
├── src/
├── tests/
├── models/
├── scripts/
├── requirements.txt
├── README.md
└── .gitignore