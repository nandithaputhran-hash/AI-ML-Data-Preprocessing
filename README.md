# AI/ML Data Preprocessing & Feature Engineering

## Project Overview

This project demonstrates data preprocessing and feature engineering techniques
using the Titanic dataset.

The main objective is to clean the raw data, handle missing values, encode
categorical variables, scale numerical features, and prepare the dataset for
machine learning.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Dataset

The Titanic dataset is used for this project.

The target variable is:

- `survived` - indicates whether a passenger survived.

## Data Preprocessing

The following preprocessing techniques were performed:

1. Exploratory Data Analysis
2. Missing value analysis
3. Duplicate value checking
4. Outlier detection
5. Data distribution analysis
6. Numerical missing value imputation using median
7. Categorical missing value imputation using most frequent value
8. One-Hot Encoding for nominal categorical variables
9. Ordinal Encoding for ordered categorical variables
10. Standard Scaling of numerical features

## Feature Engineering

Two new features were created:

### Family Size

```text
family_size = sibsp + parch + 1
