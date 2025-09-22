# Titanic Data Cleaning & Preprocessing

## Description
This repository demonstrates step-by-step data cleaning and preprocessing on the Titanic dataset. The goal is to prepare the dataset for machine learning by handling missing values, encoding categorical variables, scaling numerical features, and detecting/treating outliers.  

## Features
- Handles missing values with median (for numeric features) and mode (for categorical features).
- Encodes categorical variables using one-hot encoding.
- Detects outliers using boxplots and caps them using the IQR method.
- Scales numeric features using standardization (z-score).
- Saves cleaned dataset and visualizations for easy reference.
- Prepares data for ML tasks such as classification.

## Folder Structure
titanic-data-cleaning/
│
├── data/
│ ├── titanic.csv # Original raw dataset
│ ├── titanic_clean.csv # Cleaned dataset ready for ML
│ └── missing_after_imputation.csv # Missing values summary after imputation
│
├── figures/
│ ├── histograms_age_fare.png # Age and Fare distribution plots
│ └── boxplots_age_fare.png # Age and Fare boxplots for outlier detection
│
├── notebooks/
│ └── titanic_data_cleaning.ipynb # Full Jupyter Notebook with all steps
│
├── README.md # This file
└── .gitignore # Optional: ignore pycache, .ipynb_checkpoints, etc.

bash
Copy code

## Usage
1. Clone the repository:
```bash
git clone https://github.com/your-username/titanic-data-cleaning.git
Open the notebook notebooks/titanic_data_cleaning.ipynb in Jupyter Notebook or Jupyter Lab.

Run all cells step by step to reproduce data cleaning, visualization, and preprocessing.

Check the data/ folder for cleaned dataset and missing value summary, and figures/ for plots.

Requirements
Python 3.x

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

bash
Copy code
pip install pandas numpy matplotlib seaborn scikit-learn
Author
Your Name

References
Titanic Dataset: Kaggle Titanic Dataset

Data cleaning & preprocessing concepts from standard ML workflows.

pgsql
Copy code

If you want, I can also **rewrite the full notebook code** so it automatically saves all figures and tables into the proper `data/` and `figures/` folders to match this README perfectly. Do you want me to do that next?
