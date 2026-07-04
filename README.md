# Height Weight Prediction using Linear Regression

A Machine Learning project that predicts a person's weight based on their height using Linear Regression.

## Overview

This project demonstrates the complete machine learning workflow:
- Data Loading
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Scaling
- Train Test Split
- Linear Regression Model Training
- Model Evaluation
- Prediction on New Data

## Dataset

The dataset contains height and weight information.

Features:
- Height: Independent variable
- Weight: Target variable

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn

## Workflow

1. Import required libraries
2. Load dataset
3. Perform exploratory data analysis
4. Visualize relationship between height and weight
5. Split dataset into training and testing data
6. Train Linear Regression model
7. Evaluate model performance

## Model Used

Linear Regression

Linear Regression finds the best fit line between input and output variables.

Formula:

y = mx + c

where:
- y = predicted value
- m = coefficient
- x = input feature
- c = intercept

## Evaluation Metrics

Model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

## Results

The model successfully learned the relationship between height and weight and can predict weight for unseen height values.

## Future Improvements

- Add more features like age and gender
- Try Polynomial Regression
- Deploy model using Flask/Streamlit
