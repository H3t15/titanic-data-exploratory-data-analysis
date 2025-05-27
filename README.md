# Titanic Dataset Exploratory Data Analysis (EDA)

## Overview
This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, trends, and anomalies within the data. The goal is to gain a better understanding of the factors affecting passenger survival through statistical summaries and visualizations.

## Dataset
The dataset used is the Titanic passenger list, including information such as:

- PassengerId
- Survived (0 = No, 1 = Yes)
- Pclass (Passenger Class)
- Name
- Age
- SibSp (Number of siblings/spouses aboard)
- Parch (Number of parents/children aboard)
- Ticket
- Fare
- Cabin
- One-hot encoded columns: Sex_male, Embarked_Q, Embarked_S

## Tools and Libraries Used
- Python 3
- Pandas
- Matplotlib
- Seaborn

## Analysis Performed

### 1. Summary Statistics
- Generated basic statistics (mean, median, std, etc.) to understand data distribution.

### 2. Visualizations
- Histograms and boxplots of numeric features (Age, Fare) to assess distributions and identify outliers.
- Bar plots of survival rates by gender and passenger class.
- Distribution plots of Age and Fare split by survival status.
- Boxplots to identify anomalies and outliers in Age and Fare.

### 3. Correlation Matrix
- Calculated and visualized the correlation matrix of numeric features to explore relationships.

### 4. Patterns, Trends, and Anomalies Identified
- Females (Sex_male=0) have a notably higher survival rate than males.
- First-class passengers (Pclass=1) have higher survival rates compared to second and third class.
- Younger passengers have a higher chance of survival.
- Higher fares correlate with higher survival rates, implying socio-economic status influenced survival chances.
- Presence of outliers in Fare with some passengers paying significantly higher fares.
- Age feature contains missing values and outliers which may affect model performance.
