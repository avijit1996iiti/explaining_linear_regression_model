# Boston Housing Price Prediction

## Overview:

This project demonstrates the application of linear regression to predict housing prices in Boston using the famous Boston Housing dataset. Linear regression is a fundamental statistical and machine learning technique used for predicting a continuous dependent variable based on one or more independent variables.
Project Structure:

    code/: Directory containing the required code for linear regression model implementation.

    data/: Directory containing the Boston Housing dataset (boston.csv).

    README.md: This file explaining the project, its structure, and how to run it.

## Requirements:

    todo: revisit later

## How to Run:

    Clone the repository:

    bash
#todo: revisit later
git clone insert link
cd add name of the project folder 

## Install the required libraries:

bash

pip install -r requirements.txt


## Dataset:

The Boston Housing dataset is a famous dataset in the field of machine learning and statistics. It was collected by Harrison and Rubinfeld in 1978 and is often used for regression analysis and predictive modeling. Here's an explanation of the dataset:
### Description:

    Target Variable:
        MEDV: Median value of owner-occupied homes in $1000s. This is the variable we want to predict. It serves as the dependent variable in regression models.

    Features (Independent Variables):
        CRIM: Per capita crime rate by town.
        ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.
        INDUS: Proportion of non-retail business acres per town.
        CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise).
        NOX: Nitric oxides concentration (parts per 10 million).
        RM: Average number of rooms per dwelling.
        AGE: Proportion of owner-occupied units built prior to 1940.
        DIS: Weighted distances to five Boston employment centers.
        RAD: Index of accessibility to radial highways.
        TAX: Full-value property tax rate per $10,000.
        PTRATIO: Pupil-teacher ratio by town.
        B: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town.
        LSTAT: Percentage of lower status of the population.

### Interpretation:

    MEDV (Target):
        A higher MEDV indicates a higher median value of homes, which could be desirable for homeowners.

    Features:
        CRIM: Towns with higher crime rates might have lower housing values.
        RM: A higher average number of rooms per dwelling may correlate with higher home values.
        LSTAT: A higher percentage of lower-status population might correlate with lower home values.

## The project covers:

    Data exploration and visualization. #todo : revisit later 
    Implementation of a linear regression model using the statsmodels library.
    Interpretation of model summary and coefficients.
    Visualization of predicted vs. actual housing prices. #todo : revisit later

## Conclusion:

This project provides a hands-on example of using linear regression for housing price prediction. It serves as a valuable resource for understanding regression analysis, feature selection, and model interpretation using real-world data.

Feel free to explore and modify the code to enhance your understanding of linear regression and its application to real estate datasets. Happy coding!