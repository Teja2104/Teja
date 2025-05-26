Titanic Dataset - Data Cleaning & Preprocessing
This repository contains a Jupyter Notebook that walks through the process of cleaning and preprocessing the Titanic dataset. The goal is to prepare the data for machine learning by handling missing values, encoding categorical variables, normalizing features, and removing outliers.

Files Included
Titanic-Dataset.csv - The original Titanic dataset (not included here due to file size, but should be uploaded).

Titanic_Preprocessing.ipynb - The main Jupyter Notebook with step-by-step data preprocessing.

Titanic-Dataset-CLEANED.csv - The cleaned and preprocessed dataset ready for ML.

Steps Performed
Importing Required Libraries

pandas, numpy, matplotlib, seaborn, sklearn

Loading the Dataset

Used pandas.read_csv() to load Titanic data.

Exploratory Data Analysis

Checked for null values, data types, and basic statistics.

Handling Missing Values

Filled missing Age values with the median.

Filled missing Embarked values with the mode.

Dropped the Cabin column due to a high number of missing values.

Dropping Irrelevant Columns

Removed Name and Ticket as they are not directly useful for prediction.

Encoding Categorical Variables

Used Label Encoding for Sex.

Applied One-Hot Encoding for Embarked.

Normalizing Numerical Features

Standardized Age and Fare using StandardScaler.

Visualizing and Removing Outliers

Boxplots used for identifying outliers.

Removed outliers using the IQR (Interquartile Range) method.

Saving the Cleaned Dataset

Final dataset saved as Titanic-Dataset-CLEANED.csv.

The cleaned dataset contains no missing values, encoded categorical features, normalized numerical features, and has outliers removed for better ML performance.

Clone the repository.

Make sure you have Python and Jupyter Notebook installed.

Open Titanic_Preprocessing.ipynb and run all cells.

pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Titanic_Preprocessing.ipynb
Requirements
Python 3.x

pandas, numpy, matplotlib, seaborn, scikit-learn
