# Titanic Survival Analysis

Exploratory data analysis of the Titanic dataset to identify patterns in passenger survival rates using Python and Pandas.

## Overview

This project analyzes passenger data from the Titanic to answer questions such as:
- Did gender affect survival rate?
- Did passenger class affect survival rate?
- How do gender and class interact together?

## Tools Used

- Python
- Pandas (data cleaning and analysis)
- Matplotlib (data visualization)
- Google Colab (development environment)

## Data Source

[Titanic Dataset - Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

## Process

1. **Data Loading** — imported the dataset using `pandas.read_csv()`
2. **Data Cleaning**
   - Filled missing `Age` values with the median
   - Dropped the `Cabin` column (77% missing values)
   - Dropped rows with missing `Embarked` values
3. **Analysis**
   - Calculated survival rate by gender
   - Calculated survival rate by passenger class
   - Calculated survival rate by gender and class combined
4. **Visualization** — created bar charts to compare survival rates

## Key Findings

- Female passengers had a significantly higher survival rate than male passengers
- First-class passengers had a higher survival rate than third-class passengers
- Even third-class women had a higher survival rate than first-class men, showing gender had a stronger effect than class alone

## How to Run

1. Clone this repository
2. Open `titanic_analysis.ipynb` in Jupyter Notebook or Google Colab
3. Make sure the dataset file is in the same directory
4. Run all cells

## Author

Abdulrahman Mamou — Practical Informatics student at HTW Saar
