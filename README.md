# Titanic Data Cleaning & Preprocessing #

A step-by-step project to clean and preprocess the Titanic dataset.
This project is for data science learners or enthusiasts who want to understand:
Handling missing values

- Encoding categorical variables

- Scaling numerical features

- Detecting and treating outliers

- Preparing the dataset for machine learning

## Project Overview

This project demonstrates preprocessing the Titanic dataset from raw data to a clean, ML-ready dataset. Key steps include:

Loading and exploring the dataset

Handling missing values (median for numeric, mode for categorical)

Encoding categorical variables using one-hot encoding

Outlier detection using boxplots and IQR capping

Standardizing numerical features

Saving necessary figures and cleaned dataset                  

## How to Use

1. Clone the repository:
```bash

git clone <your-repo-link>
```

2. Open the Jupyter Notebook:
```bash

jupyter notebook titanic_data_cleaning.ipynb
```

3. Run the notebook cells sequentially to:

-> View dataset exploration

-> Verify missing value handling

-> Generate plots for distributions and outliers

-> Save the cleaned dataset and figures

## Running Tests

This project does not include automated tests. To verify preprocessing steps:

Open the notebook titanic_data_cleaning.ipynb.

## Tech Stack

Client: Jupyter Notebook, Matplotlib, Seaborn, Pandas, NumPy
Server: Python 3.x

## Acknowledgements

Seaborn: statistical data visualization

Pandas Documentation

Scikit-learn Preprocessing
