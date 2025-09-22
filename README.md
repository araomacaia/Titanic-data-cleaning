## Titanic Data Cleaning & Preprocessing

A step-by-step project to clean and preprocess the Titanic dataset.
This project is for data science learners or enthusiasts who want to understand:

Handling missing values

Encoding categorical variables

Scaling numerical features

Detecting and treating outliers

Preparing the dataset for machine learning

Project Overview

This project demonstrates preprocessing the Titanic dataset from raw data to a clean, ML-ready dataset. Key steps include:

Loading and exploring the dataset

Handling missing values (median for numeric, mode for categorical)

Encoding categorical variables using one-hot encoding

Outlier detection using boxplots and IQR capping

Standardizing numerical features

Saving necessary figures and cleaned dataset

Folder Structure
titanic_project/
│
├── titanic_data_cleaning.ipynb   # Jupyter Notebook with all preprocessing steps
├── titanic.csv                   # Original dataset
├── titanic_clean.csv             # Cleaned dataset
├── histograms_age_fare.png       # Histograms of Age and Fare
├── boxplots_age_fare.png         # Boxplots of Age and Fare
├── missing_after_imputation.csv  # Missing value summary after imputation
└── README.md                     # Project documentation

How to Use

Clone the repository:

git clone <your-repo-link>


Open the Jupyter Notebook:

jupyter notebook titanic_data_cleaning.ipynb


Run the notebook cells sequentially to:

View dataset exploration

Verify missing value handling

Generate plots for distributions and outliers

Save the cleaned dataset and figures

Running Tests

This project does not include automated tests. To verify preprocessing steps:

Open the notebook titanic_data_cleaning.ipynb.

Run cells sequentially.

Check outputs:

Missing value summary (missing_after_imputation.csv)

Outlier detection plots (boxplots_age_fare.png)

Histograms (histograms_age_fare.png)

Final cleaned dataset (titanic_clean.csv)

Tech Stack

Client: Jupyter Notebook, Matplotlib, Seaborn, Pandas, NumPy
Server: Python 3.x

Acknowledgements

Seaborn: statistical data visualization

Pandas Documentation

Scikit-learn Preprocessing
