# Syntecxhub Titanic Dataset EDA
Data Science Week 3 Task 1\
Author: Debojit Roy Chowdhury

**Resources:**\
* Dataset - https://www.kaggle.com/c/titanic
* Pandas - https://pandas.pydata.org/docs/
* Seaborn Visuals - https://seaborn.pydata.org/
* Matplot Library - https://matplotlib.org/stable/gallery/index.html
* Scikit-learn (Optional) - https://scikit-learn.org/stable/

-----

## Overview

This project focuses on analyzing the Titanic dataset to understand survival patterns among passengers. Using data analysis and visualization techniques, the project explores how factors like gender, passenger class, and age influenced survival outcomes.

## Objectives
* Load and inspect the Titanic dataset
* Identify missing values and understand data types
* Analyze survival rates based on:

  * Gender
  * Passenger Class
  * Age groups
* Visualize findings using charts
* Extract meaningful insights from the data

## Dataset
The dataset used is the Titanic dataset from Kaggle, which contains passenger details such as:
* PassengerId
* Survived
* Pclass
* Name
* Sex
* Age
* Fare
* Embarked

## Technologies Used

* Python
* Pandas
* Seaborn
* Matplotlib
* Jupyter Notebook

## Key Analysis

### Data Inspection
* Checked dataset structure using `.info()` and `.columns()`
* Identified missing values in Age, Cabin, and Embarked

### Survival Distribution
* Compared number of survivors vs non-survivors
* Observed that more passengers did not survive

### Survival by Gender
* Female passengers showed significantly higher survival rates than males

### Survival by Passenger Class
* First-class passengers had better survival chances
* Third-class passengers had the highest number of deaths

### Age Group Analysis
* Created age buckets: Child, Teen, Adult, Senior
* Compared survival across age groups

### Age Distribution
* Used boxplot to visualize age distribution among survivors and non-survivors

## Visualizations
The following plots were created and saved:
* Survival Count
* Survival by Gender
* Survival by Passenger Class
* Survival by Age Group
* Age Distribution (Boxplot)

## Key Insights
* Female passengers had significantly higher survival rates compared to males
* First-class passengers had better survival chances than lower classes
* Third-class passengers had the highest number of deaths
* Children showed relatively higher survival rates
* The number of non-survivors was greater than survivors

## How to Run the Project
1. Clone the repository:

```bash
git clone https://github.com/DebojitRC/Syntecxhub_Titanic_EDA
```

2. Navigate to the project folder:

```bash
cd Syntecxhub_Titanic_EDA
```

3. Install required libraries:

```bash
pip install pandas seaborn matplotlib
```

4. Run the Jupyter Notebook:

```bash
jupyter notebook
```

## Future Scope
* Perform feature engineering (e.g., family size, titles)
* Apply machine learning models for survival prediction
* Build interactive dashboards using Plotly or Power BI

## Conclusion

This project demonstrates how exploratory data analysis can uncover meaningful patterns in data. Factors such as gender, passenger class, and age significantly influenced survival outcomes on the Titanic.
