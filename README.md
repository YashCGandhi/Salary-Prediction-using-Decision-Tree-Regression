# Salary-Prediction-using-Decision-Tree-Regression
This repository contains code for performing decision tree regression analysis using the sklearn library. The code involves data preprocessing, building decision tree regressor models, and evaluating their performance.
The data file can be found at https://www.kaggle.com/datasets/siddheshera/san-francisco-employee-salary-compensation

## Overview

The code performs decision tree regression analysis on employee salary compensation data. It covers the following steps:

1. **Data Preprocessing**: The provided CSV dataset (`Employee_Salary_Compensation.csv`) is read using Pandas. Redundant and insignificant columns are dropped, missing values are handled, and negative or zero compensation values are removed.

2. **Encoding Categorical Variables**: The LabelEncoder from Scikit-learn is used to encode categorical values into numerical values.

3. **Decision Tree Regressor**: The baseline DecisionTreeRegressor from Scikit-learn is used to build decision tree models. The code creates multiple models with varying maximum depths and evaluates them using Mean Squared Error, Root Mean Squared Error, Mean Absolute Error, and R-squared score.

4. **Custom Decision Tree Regressor**: A custom decision tree regressor is implemented. The code provides a Node class to represent nodes in the tree, and a DecisionTreeRegressor class to build and use the custom decision tree regressor.

5. **Evaluation**: The custom decision tree regressor is evaluated on the same dataset, comparing its performance against the sklearn decision tree regressor.

## Execution

1. Clone or download this repository to your local environment.

2. Make sure you have the required libraries installed using the provided prerequisites.

3. Place the `Employee_Salary_Compensation.csv` dataset in the same directory as the code.

4. Open and run the code in a Python environment or Jupyter notebook.

## Results

The code demonstrates decision tree regression analysis on employee salary compensation data. It builds decision tree models using both the sklearn library and a custom implementation. The performance of these models is evaluated using various metrics, including Mean Squared Error, Root Mean Squared Error, Mean Absolute Error, and R-squared score.

Feel free to explore, modify, and extend the code for your specific analysis or datasets.

## Author

Yash Chinmay Gandhi
