# 25_Machine-Learning_Lab1

## EDA

### Objective

The objective of this practical is to perform fundamental Exploratory Data Analysis (EDA) and data preprocessing techniques on the Titanic Dataset.

### Files

- **ML_Lab1.ipynb**: The Jupyter Notebook containing the Python code for the practical.
- **Titanic-Dataset.csv**: The raw dataset used for analysis, containing passenger survival information and demographics from the Titanic.

## Practical Steps Covered

### 1. Data Loading & Inspection

- Loading the dataset into a DataFrame using Pandas.
- Inspecting the data structure using:
  - `.head()`
  - `.tail()`
  - `.shape`
  - `.info()`
  - `.describe()`

### 2. Data Cleaning

- Identifying missing values using `.isnull().sum()`.
- Imputing missing values:
  - Filling `Age` with the median.
  - Filling `Embarked` with the mode.
- Dropping columns with excessive missing data, such as the `Cabin` column.

### 3. Data Quality Checks

- Checking for and handling duplicate records in the dataset.

### 4. Outlier Detection & Handling

- Visualizing the distribution and potential outliers of variables such as `Age` and `Fare` using boxplots with Seaborn.
- Removing outliers from the `Age` variable using the Interquartile Range (IQR) method.

## Requirements

To run the notebook, ensure you have the following installed:

1. Python 3.x
2. Pandas
3. NumPy
4. Matplotlib
5. Seaborn
