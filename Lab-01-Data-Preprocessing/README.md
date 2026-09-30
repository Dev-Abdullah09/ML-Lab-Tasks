
# Lab Task 01 – Data Preprocessing

## Course

Machine Learning

## Lab Task

Complete data preprocessing for two different datasets:

1. House Prices Dataset
2. Stock Market Historical Dataset

## Objective

The objective of this lab task is to perform complete data preprocessing on both datasets separately and understand how preprocessing strategies differ depending on the nature and characteristics of the data.

## Datasets

### 1. House Prices Dataset

The House Prices dataset contains information about residential properties and their features, which can be used for predicting house prices.

The preprocessing includes tasks such as:

* Handling missing values
* Identifying numerical and categorical features
* Handling categorical variables
* Detecting and handling outliers where appropriate
* Feature scaling where required
* Preparing the data for machine learning

### 2. Stock Market Dataset

The Stock Market dataset contains historical stock market information such as price and trading-related attributes.

The preprocessing includes tasks such as:

* Handling missing values
* Converting and processing date/time information
* Sorting observations chronologically
* Checking duplicate records
* Handling numerical features
* Detecting anomalous values
* Preparing historical data for analysis and forecasting

## Key Difference in Preprocessing

The House Prices dataset is primarily a tabular dataset containing numerical and categorical property features. Therefore, preprocessing focuses heavily on missing values, categorical encoding, feature transformation, and preparation of independent variables.

The Stock Market dataset is time-series data. Therefore, chronological ordering, date/time processing, temporal structure, and avoiding data leakage from future observations are particularly important.

## Files

```text
datasets/
├── house_prices.csv
└── stock_market.csv

Lab_01_Data_Preprocessing.ipynb
README.md
```

## Notebook

The complete implementation and preprocessing steps are available in:

`Lab_01_Data_Preprocessing.ipynb`
