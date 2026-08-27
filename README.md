# Task 1: Data Cleaning & Preprocessing

## Internship Task

**AI & ML Internship — Elevate Labs**

## Objective

The objective of this task is to clean and prepare raw data for machine learning.

## Dataset

The Titanic passenger dataset was used for this task. The dataset contains passenger information and survival status.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Data Preprocessing Steps

The following preprocessing steps were performed:

1. Imported and explored the dataset.
2. Checked for missing values and data types.
3. Handled missing values using median and mode imputation.
4. Removed the `Cabin` column because it contained a large number of missing values.
5. Identified numerical and categorical features.
6. Removed unnecessary identifier columns such as `PassengerId`, `Name`, and `Ticket`.
7. Converted categorical variables into numerical values using one-hot encoding.
8. Visualized potential outliers using boxplots.
9. Detected and removed outliers using the IQR method.
10. Standardized numerical features using `StandardScaler`.
11. Verified that the final dataset contained no missing values.
12. Saved the preprocessed dataset as `Titanic_Preprocessed.csv`.

## Project Files

* `Task_1_Data_Cleaning_Preprocessing.ipynb` — Jupyter Notebook containing the complete preprocessing workflow.
* `train.csv` — Original Titanic dataset.
* `Titanic_Preprocessed.csv` — Final cleaned and preprocessed dataset.
* `README.md` — Project documentation.

## Result

The Titanic dataset was successfully cleaned and transformed into a machine-learning-ready format. Missing values were handled, categorical variables were encoded, outliers were removed, and numerical features were standardized.

## Conclusion

This project demonstrates the basic data cleaning and preprocessing steps required before using a dataset for machine learning.
