# 🧹 Data Cleaning & Preprocessing of the Titanic Dataset

This repository contains my work for **Task 1** of my AI & ML Internship, where I focused on **data cleaning and preprocessing** using the Titanic dataset.  
The main objective of this task was to **learn how to clean raw data and prepare it for machine learning**.  

---

## 📖 What I Did (Step by Step)

1. **Loading the Data**  
   - I used **Pandas** to load the Titanic dataset (`titanic.csv`) into my Jupyter Notebook.  
   - I explored the dataset with `.head()`, `.info()`, and `.describe()` to understand its structure, data types, and missing values.

2. **Handling Missing Values**  
   - I filled missing values in `age` and `fare` with their **median**.  
   - I filled missing values in `embarked` with the **most frequent value (mode)**.  
   - This helped ensure there were no empty cells blocking the preprocessing pipeline.

3. **Encoding Categorical Variables**  
   - I used **One-Hot Encoding** to transform `sex` and `embarked` into numerical format.  
   - For demonstration, I also tried **Label Encoding** on `sex` to highlight the difference.

4. **Outlier Detection & Treatment**  
   - I visualized distributions of `age` and `fare` with **boxplots**.  
   - Outliers were detected and treated using the **IQR method**, which capped extreme values.

5. **Feature Scaling**  
   - I standardized numeric features (`age`, `sibsp`, `parch`, `fare`) using **z-score scaling**.  
   - This ensured all features had a similar scale, important for ML models.

6. **Saving the Cleaned Dataset**  
   - Finally, I saved the cleaned and preprocessed dataset as `titanic_clean.csv`.  

---

## 📂 Repository Structure

```
Data-Cleaning-Preprocessing-Titanic/
│── Books_Reffered/
│ └── Books
│── Dataset/
│ └── titanic.csv
│── Outputs/
│ └── Cleaned_data/
│  ├── titanic_clean.xls
│ └── Figures/
│  ├── boxplots_after_capping.png
│  ├── boxplots_age_fare.png
│ └── Jupyter_Notebook/
│  ├── Tak1_Cleaning-&-Prepocessing.ipynb
│ └── Tables/
│  ├── titanic_clean.csv 
│  ├── missing_values_summary.csv
│  ├── descriptive_stats.csv 
│  ├── boxplots_age_fare.png 
│  └── scaled_data_preview.csv 
│── README.md
```

---

## ⚙️ Tech Stack
For this task, I worked with:
- **Python 3.x**  
- **Pandas** → summary statistics & data handling  
- **NumPy** → numerical operations  
- **Matplotlib & Seaborn** → visualization (histograms, boxplots, heatmaps, pairplots)  
- **Jupyter Notebook** → interactive analysis  

---

## 📚 Acknowledgements & References
During this task, I referred to the following books and resources:

- *Data Pre-processing: Clean, Reduce and Transform* — Anran Zhao  
- *Efficient Data Cleaning and Preprocessing Techniques for Robust Machine Learning Models* — Dr. Charalambos Chrysostomou  
- *Data Cleaning and Preprocessing for Data Science Beginners* — Data Science Horizons  
- *Data Preprocessing: the Techniques for Preparing Clean and Quality Data for Data Analytics Process* — Ashish P. Joshi & Biraj V. Patel  
- *Machine Learning* — Anuradha Srinivasaraghavan & Vincy Joseph  
- *Python for Data Analysis* — Wes McKinney  
- *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* — Aurélien Géron  
- *Practical Statistics for Data Scientists* — Peter Bruce & Andrew Bruce  
- *Data Science from Scratch* — Joel Grus  
- *Storytelling with Data* — Cole Nussbaumer Knaflic  
- *Introduction to Machine Learning with Python* — Andreas C. Müller & Sarah Guido  
- Online documentation of Pandas, Seaborn, Matplotlib, and Scikit-learn  
- Titanic dataset available on [Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## 📝 Author
**Arao Zau Macaia**  
AI & ML Internship Task2 (2025)
