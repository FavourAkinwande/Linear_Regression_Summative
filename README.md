# Linear_Regression_Summative

Overview
This project implements a linear regression model to predict outcomes based on a given set of input features. The model utilizes various machine learning algorithms, including Linear Regression, Random Forest, and Decision Trees, to compare their performances based on Root Mean Square Error (RMSE).

Features
Data Preprocessing: Converts data into appropriate formats for model training.
Model Implementation:
Linear Regression
Random Forest Regressor
Decision Tree Regressor
Performance Evaluation: Calculates RMSE for each model and ranks them from best to worst.
Requirements
Make sure to install the following Python libraries:

NumPy
Pandas
Scikit-Learn
You can install these using pip:

bash
Copy code
pip install numpy pandas scikit-learn
Usage
Load Data: Replace the sample data in the code with your dataset.
Run the Models: Execute the script to train the models and compare their performance.
View Results: The RMSE values will be printed, showing the ranking of each model.
Example
Here’s a brief example of how to define the models and evaluate their performance:

python

import numpy as np
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.ensemble import RandomForestRegressor
from sklearn.tree import DecisionTreeRegressor
from sklearn.metrics import mean_squared_error


X = np.array([...])  # Input features
Y = np.array([...])  # Output values

X_train, X_test, Y_train, Y_test = train_test_split(X, Y, test_size=0.2, random_state=42)

Train models
Linear Regression, Random Forest, Decision Tree code here...

Evaluate and print RMSE
License
This project is licensed under the MIT License. See the LICENSE file for more details.
