# Personal Income Prediction from Census Data

## Project Objective

This project aims to develop a personal income prediction model based on census data. The main objective of this project is to predict whether a person has an income above or below a certain threshold based on the features present in the census data.

## Problem Solved

The problem solved in this project is how to predict a person's personal income based on features such as age, education, occupation, marital status, and others. With this prediction model, it can help in government policy planning, market analysis, and other decision making related to personal income.

## Background of the Problem

Understanding an individual's personal income is crucial in many aspects of life, including financial planning, socioeconomic analysis, and government policy. Therefore, having an accurate prediction model to predict personal income based on census data can provide valuable insights to various fields.

## Project Output

The output of this project is a prediction model that can accept an individual's census data as input and output a prediction of whether the individual has an income above or below a certain threshold. In addition, there will be analysis of the prediction results and interpretation of the features that are significant in income prediction.

## Brief Description of Data Used

The data used in this project is taken from the Census Adult Income dataset stored on Google BigQuery. This dataset includes various features such as age, education, occupation, marital status, number of hours worked per week, and others. The target column is "income" which indicates whether a person's income exceeds 50 thousand dollars or not.

## Methods Used

This project will use a machine learning approach to build a prediction model. The methods to be used include:

- Data pre-processing: Cleaning the data from null and duplicate values, and converting categorical variables to numerical.
- Prediction model: Using classification algorithms such as Logistic Regression, SVC (Support Vector Machine Classifier) to train the model with training data and make predictions on test data.

## Stack Used

In this project, we will use some of the following technologies and tools:

- Programming Language: Python
- Libraries and Frameworks: pandas, numpy, scikit-learn, matplotlib, seaborn
- Development Environment: Jupyter Notebook

## Brief Explanation of Contents and Purpose of Each File

This project has the following directory and file structure:

- `h8dsft_P1G2_dayuima.ipynb`: Jupyter notebook containing code for data pre-processing, containing code for training the prediction model using classification algorithms, and containing analysis of prediction results and interpretation of significant features.
- `README.md`: This README file contains an explanation of the project.

## Advantages and Disadvantages of the Project

The strengths of this project are:

- Can provide a prediction model that can be used to predict personal income based on features in census data.
- Uses a machine learning approach that can provide accurate prediction results.

Disadvantages of this project are:

- Prediction results can be affected by the choice of classification algorithms and parameters used.