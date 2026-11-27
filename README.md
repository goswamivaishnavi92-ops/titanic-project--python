# titanic-project--python







Titanic Dataset — Exploratory Data Analysis
A beginner-friendly Python data analysis project exploring the Titanic passenger dataset with Pandas, NumPy, Matplotlib, and Seaborn. The notebook loads the Titanic dataset, inspects passenger records, and focuses on understanding the distribution and missing values of the age feature through summary statistics and visualizations.

Project Overview
The goal of this project is to practise exploratory data analysis (EDA) and understand how a dataset can be inspected and visualized before deeper analysis.

The notebook uses Seaborn's built-in Titanic dataset:

df = sns.load_dataset("titanic")
It displays a sample of passenger records and explores the age column using descriptive statistics, missing-value checks, and plots.

Tools & Libraries
Python — programming language
Pandas — data loading and DataFrame operations
NumPy — numerical operations
Matplotlib — data visualization
Seaborn — sample dataset and statistical visualization
Dataset
The dataset contains passenger-related information, including fields such as:

Column	Description
survived	Survival indicator (0 = No, 1 = Yes)
pclass	Passenger class
sex	Passenger sex
age	Passenger age
sibsp	Number of siblings/spouses aboard
parch	Number of parents/children aboard
fare	Passenger fare
embarked	Port of embarkation
class	Passenger class label
who	Passenger category
deck	Cabin deck
embark_town	Town of embarkation
alive	Survival label
alone	Whether the passenger was travelling alone
Work Performed
1. Importing libraries
Imported Pandas, NumPy, Seaborn, and Matplotlib for data handling and visualization.

2. Loading and inspecting the data
Loaded the Titanic dataset with sns.load_dataset("titanic") and viewed a sample of 30 records to become familiar with its columns and values.

3. Exploring the age column
Used describe() to review the count, mean, standard deviation, minimum, quartiles, and maximum age values.

4. Checking missing values
Used isna().sum() to count missing values in the age column. The notebook output shows 177 missing age values.

5. Visualizing age distribution
Created:

A histogram of passenger ages.
A histogram with specified age bins and axis/title labels.
A Seaborn KDE plot to view the shape of the age distribution.
A box plot to inspect the spread and potential outliers.
6. Checking skewness
Used the Pandas skew() method to examine the skewness of the age distribution. The notebook output reports approximately 0.389, indicating a positively skewed distribution.

How to Run the Project
Clone or download this repository.

Open the project notebook in Jupyter Notebook, JupyterLab, or Google Colab.

Install the required libraries if they are not already available:

pip install pandas numpy matplotlib seaborn jupyter
Launch Jupyter Notebook:

jupyter notebook
Open the Titanic project notebook and run the cells from top to bottom.

Note: The notebook loads the dataset directly through Seaborn. An internet connection may be required the first time the dataset is downloaded or if it is not cached locally.

Key Observations
The age column contains 177 missing values in the notebook's dataset.
The descriptive-statistics output is based on 714 non-missing age records.
The notebook reports an age-distribution skewness of approximately 0.389.
Histograms, a KDE plot, and a box plot are used to explore the age distribution.
Project Scope
This repository represents an exploratory data analysis exercise, with particular attention to the age column. The notebook does not currently document a completed machine-learning model, survival prediction, model evaluation, or a full analysis of every dataset feature. Those can be added as future extensions.

Future Improvements
Explore survival rates by passenger class, sex, and age.
Compare age distributions across survival groups.
Investigate missing values in other columns.
Perform data cleaning and feature engineering.
Build and evaluate a machine-learning model to predict survival.
Skills Demonstrated
Python · Pandas · NumPy · Matplotlib · Seaborn · Exploratory Data Analysis · Data Visualization · Descriptive Statistics · Missing-Value Analysis

Author: vaishnavi
Project: Titanic Dataset — Exploratory Data Analysis
Purpose: Python and data analytics learning project





