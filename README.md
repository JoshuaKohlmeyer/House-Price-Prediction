# Predicting House Prices by Training Models in R

[![GitHub Pages](https://img.shields.io/badge/Live%20Project-View%20Website-brightgreen)](https://joshuakohlmeyer.github.io/House-Price-Prediction/)

Predicting residential house prices using machine learning models in R.  
An end to end housing price prediction project built using **R** and **tidymodels**.

This repository includes a **fully rendered HTML report** that demonstrates the complete analysis, visualizations, and final model results in a clear and reproducible way.

---

## Project Overview

The aim of this project was to apply everything I learnt about machine learning in R to a single, realistic problem. Instead of focusing on theory alone, I wanted to build a full, practical workflow that mirrors how predictive models are used in real life.

Using the Ames Housing dataset, I built and compared multiple models to predict residential house prices. The project covers the full machine learning pipeline, from exploratory data analysis to feature engineering, model training, tuning, evaluation, and interpretation.

This project was done to strengthen my applied skills in **R**, **machine learning**, and **statistical modeling**, using both university coursework and self study as a foundation.

---

## Dataset

- **Dataset**: Ames Housing Dataset  
- **Source**: https://www.kaggle.com/datasets/prevek18/ames-housing-dataset  
- **Description**: Detailed information on residential properties in Ames, Iowa.  
  House prices are in US dollars ($) and measurements are in feet (ft).  
  The predictive model can easily be adapted to South African metrics when required.
- **Target Variable**: Sale price

The dataset contains a rich mix of numeric and categorical variables describing house size, quality, location, and condition, making it ideal for real world price prediction.

---

## Why I Did This Project

I built this project to:

- Apply machine learning concepts learnt in university coursework and self study
- Practice using R for real world predictive modeling
- Gain hands on experience with **tidymodels** and model workflows
- Move beyond theory and demonstrate a complete end to end implementation

This project combines ideas from **machine learning**, **statistics**, and **data science** into one coherent analysis.

---

## Project Workflow

The analysis follows a clear and structured pipeline:

1. Loaded and cleaned the raw dataset in R  
2. Performed exploratory data analysis to understand distributions and relationships  
3. Handled missing values and categorical levels carefully  
4. Removed extreme outliers to improve model stability  
5. Applied log transformation to the target variable  
6. Engineered features using a tidymodels recipe  
7. Split the data into training and test sets  
8. Trained models using cross validation  
9. Tuned hyperparameters for tree based models  
10. Compared models using RMSE and R squared  
11. Evaluated final performance on unseen test data  
12. Visualized predictions and residuals to assess model fit  
13. Demonstrated how the model can be used for real world predictions  

All steps are fully reproducible and documented using **RMarkdown**.

---

## Project Website (Rendered Output)

The full analysis, visualizations, and model results can be viewed here:

 **https://joshuakohlmeyer.github.io/House-Price-Prediction/**

---

## Models Trained

- Linear Regression  
- Random Forest  
- XGBoost  

Each model was trained using cross validation and evaluated consistently to ensure fair comparison.

---

## Key Results

- The **XGBoost model** achieved the strongest performance
- Test set **R squared ≈ 0.81**
- The model explains about **81 percent** of the variation in house prices
- Prediction plots show strong alignment between actual and predicted prices
- Residual diagnostics indicate a well behaved model with no major systematic issues

Overall, the final model performs very well and produces realistic price estimates.

---

## Practical Application

This project demonstrates how a trained machine learning model can be used to:

- Predict the market value of a house based on its features
- Understand how changes in inputs affect price
- Support pricing decisions in a real estate context
- Translate statistical models into actionable insights

The same workflow can be applied to many real world prediction problems beyond housing data.

---

## Visual Highlights

- Predictions vs Actual Sale Price plot
- Residual diagnostics plot
- Model comparison table
- Feature importance visualization

---

## Tools and Libraries Used

### Programming Language
- **R**

### Data Manipulation and Visualization
- **tidyverse**  
- **ggplot2**

### Machine Learning and Modeling
- **tidymodels**  
- **xgboost**  
- **ranger**

### Reporting and Reproducibility
- **RMarkdown**

---

## Contact

If you would like to connect or give feedback on this project (much appreciated):

- LinkedIn: https://www.linkedin.com/in/joshua-kohlmeyer/

- GitHub: https://github.com/JoshuaKohlmeyer

##
