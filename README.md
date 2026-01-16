# Predicting House Prices by Training Models in R
**Project Overview**

The goal of this project was to apply everything I have learned about machine learning in R to a single, realistic problem. Instead of focusing on theory alone, I wanted to build a full, practical workflow that mirrors how predictive models are used in real life.

Using the Ames Housing dataset, I built and compared multiple models to predict residential house prices. The project covers the full machine learning pipeline, from exploratory data analysis to feature engineering, model training, tuning, evaluation, and interpretation.

This project was done to strengthen my applied skills in R, machine learning, and statistical modeling, using both university coursework and self study as a foundation.

Dataset

Dataset: Ames Housing Dataset

Source: https://www.kaggle.com/datasets/prevek18/ames-housing-dataset

Description: Detailed information on residential properties in Ames, Iowa

Target variable: Sale price

The dataset contains a rich mix of numeric and categorical variables describing house size, quality, location, and condition, making it ideal for real world price prediction.

Why I did this project

I built this project to:

Apply machine learning concepts learned in university coursework

Practice using R for real world predictive modeling

Gain hands on experience with tidymodels and model workflows

Move beyond theory and show practical, end to end implementation

Create a portfolio project that clearly demonstrates applied skills

This project combines ideas from machine learning, statistics, and data science into one coherent analysis.

Project Workflow

The analysis follows a clear and structured pipeline:

Loaded and cleaned the raw dataset in R

Performed exploratory data analysis to understand distributions and relationships

Handled missing values and categorical levels carefully

Removed extreme outliers to improve model stability

Applied log transformation to the target variable

Engineered features using a tidymodels recipe

Split the data into training and test sets

Trained models using cross validation

Tuned hyperparameters for tree based models

Compared models using RMSE and R squared

Evaluated final performance on unseen test data

Visualized predictions and residuals to assess model fit

Demonstrated how the model can be used for real world predictions

All steps are fully reproducible and documented using RMarkdown.

Models Trained

Linear Regression

Random Forest

XGBoost

Each model was trained using cross validation and evaluated consistently to ensure fair comparison.

Key Results

The XGBoost model achieved the strongest performance

Test set R squared is approximately 0.81

This means the model explains about 81 percent of the variation in house prices

Prediction plots show strong alignment between actual and predicted prices

Residual diagnostics indicate a well behaved model with no major systematic issues

Overall, the model performs well and produces realistic price estimates.

Practical Application

This project shows how a trained machine learning model can be used to:

Predict the market value of a house based on its features

Understand how changes in inputs affect price

Support pricing decisions in a real estate context

Translate statistical models into actionable insights

The same workflow can be applied to many real world prediction problems beyond housing data.

Tools and Libraries Used

R

tidyverse

tidymodels

xgboost

ranger

ggplot2

RMarkdown

How to run the project

Clone or download the repository

Open the project in RStudio

Install required packages if needed

Knit the RMarkdown file to reproduce the full analysis
