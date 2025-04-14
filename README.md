# Titanic Dataset Exploratory Data Analysis (EDA)

## Project Overview

This project involves performing **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover patterns, trends, and anomalies that can help us understand the factors affecting survival. We will analyze key features such as **Age**, **Fare**, **Pclass**, **Sex**, and **Embarked** to identify relationships and trends. We will also visualize the data using various plots and statistical methods.

## Table of Contents

1. [Dataset Overview](#dataset-overview)
2. [Data Cleaning](#data-cleaning)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Visualizations](#visualizations)
5. [Summary of Findings](#summary-of-findings)

## Dataset Overview

The Titanic dataset contains information about passengers aboard the Titanic ship. The columns include:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Whether the passenger survived (1) or not (0)
- **Pclass**: Passenger's class (1st, 2nd, or 3rd)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger (some missing values)
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Fare paid by the passenger
- **Cabin**: Cabin number (many missing values)
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Data Cleaning

- **Handling Missing Values**: 
  - Missing values in **Age** were filled with the median.
  - Missing values in **Embarked** were filled with the mode.
  - **Cabin** was ignored due to a high number of missing values.
  
- **Outlier Handling**: 
  - Outliers in **Fare** and **Age** were removed to ensure the integrity of the analysis.

## Exploratory Data Analysis (EDA)

1. **Survived vs Sex**: Females had a much higher survival rate than males.
2. **Survived vs Pclass**: 1st class passengers had the highest survival, while 3rd class passengers had the lowest.
3. **Survived vs Embarked**: Passengers from Cherbourg (C) had the highest survival rate.

## Visualizations

- **Histograms**: Displayed the distribution of **Age** and **Fare**.
- **Boxplots**: Showed the spread of **Age** and **Fare**, highlighting the presence of outliers.
- **Scatterplots**: Visualized the relationship between **Age** and **Fare**.
- **Pairplots**: Illustrated relationships between different numerical features and survival.
- **Heatmap**: Showed correlations between numerical features.
- **Countplots**: Visualized the counts of categorical variables like **Survived**, **Sex**, **Pclass**.

## Summary of Findings

1. **Females had a higher survival rate** than males.
2. **1st class passengers** had a significantly higher survival rate compared to those in 2nd or 3rd class.
3. Passengers who paid **higher fares** had better survival chances.
4. The **age** distribution showed that younger passengers, especially children, had a higher chance of survival.
5. **Cherbourg** (C) had the highest survival rate in terms of embarkation points.

## Conclusion

Through this analysis, we identified key factors influencing survival on the Titanic. The insights gained can potentially be used for predictive modeling in future machine learning projects. Future steps can include applying machine learning algorithms to predict survival based on these features.

---

Feel free to customize the details to suit your specific needs!
