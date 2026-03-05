# DATA 201 – Week 3 Assignment
Visualization + Linear Regression (R → Python Bridge)

## Overview
This assignment explores the relationship between housing characteristics and price using Python. The analysis focuses on visualization, regression modeling, and prediction workflows.

## Dataset
housing.csv

Variables used:
- price
- size
- bedrooms
- neighborhood

## Part I – Visualization
Created multiple plots to explore the data:
- Scatterplot of size vs price
- Colored by neighborhood
- Faceted plots by bedrooms
- Histogram and density plot of price
- Boxplot of price by neighborhood

## Part II – Linear Regression
Fit a multiple regression model using statsmodels equivalent to:

lm(price ~ size + bedrooms + neighborhood)

Reported:
- coefficient estimates
- standard errors
- R²

## Part III – Prediction Workflow
Used scikit-learn to:
- split data into training and test sets
- train a linear regression model
- evaluate performance using RMSE and test R²

## Part IV – Integrated Visualization
Created a polished figure showing size vs price colored by neighborhood with a regression line to visually compare with model results.

## Key Insight
Housing price increases with size, and neighborhood differences influence price variation.
