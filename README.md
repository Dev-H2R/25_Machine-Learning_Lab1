# 25_Machine-Learning_Lab1
EDA 

Objective
The objective of this practical is to perform fundamental Exploratory Data Analysis (EDA) and data preprocessing techniques on the Titanic Dataset.

Files
ML_Lab1.ipynb: The Jupyter Notebook containing the Python code for the practical.
Titanic-Dataset.csv: The raw dataset used for analysis, containing passenger survival information and demographics from the Titanic.
# Practical Steps Covered
# Data Loading & Inspection:
Loading the dataset into a DataFrame using pandas.
Inspecting the data structure using .head(), .tail(), .shape, .info(), and .describe().
# Data Cleaning:
Identifying missing values using .isnull().sum().
Imputing missing values: filling Age with the median and Embarked with the mode.
Dropping columns with excessive missing data (e.g., the Cabin column).
# Data Quality Checks:
Checking for and handling duplicate records in the dataset.
# Outlier Detection & Handling:
Visualizing the distribution and potential outliers of variables like Age and Fare using boxplots (seaborn).
Removing outliers for the Age variable using the Interquartile Range (IQR) method.
Requirements
#To run the notebook, ensure you have the following installed:
1)Python 3.x
2)pandas
3)numpy
4)matplotlib
5)seaborn
