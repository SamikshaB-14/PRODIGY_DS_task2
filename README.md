# PRODIGY_DS_task2

Overview:

This repository contains Python code for data cleaning and exploratory data analysis (EDA) on the train dataset. The code aims to explore relationships between variables, identify patterns, and uncover trends within the dataset.

IDE Used - Jupyter notebook
Language - python (pandas, numpy, matplotlib, seaborn)
Steps:

1. Data Cleaning:

    Missing values in 'Age' are imputed with the mean for enhanced dataset completeness.
    'Embarked' missing values are filled with the mode to minimize data loss.
    The 'Cabin' column, characterized by a significant number of missing values, is dropped for simplicity.

2. Exploratory Data Analysis (EDA):

    Survival by Passenger Class:
        Visualizes survival counts based on passenger class using a Seaborn countplot.
        Aims to reveal potential correlations between socio-economic status (Pclass) and survival.

    Distribution of Age:
        Presents a Seaborn histogram with a kernel density estimate, illustrating the distribution of passenger ages.
        Provides insights into the demographic makeup of the dataset.

    Correlation Matrix:
        Computes and visualizes a correlation matrix for numeric variables using a Seaborn heatmap.
        Enhances understanding of interdependencies within the dataset.
