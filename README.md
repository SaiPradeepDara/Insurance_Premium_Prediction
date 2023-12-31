INSURANCE PREMIUM PREDICTION

Problem Statement :

The goal of this project is to give people an estimate of how much they need based on their individual health situation then they can work with any health insurance carrier and its plans and perks while keeping the estimated cost in mind. This can assist a person in concentrating on the health side of an insurance policy rather than the ineffective part.

Dataset: The dataset is taken from a Kaggle.

Approach: Applying machine learning tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building, and model testing to build a solution that can predict the premium of the person for health insurance.

Data Exploration: Exploring the dataset using pandas, numpy, matplotlib, and seaborn. 
Exploratory Data Analysis: Plotted different graphs to get more insights about dependent and independent variables/features. 
Feature Engineering: Numerical features scaled down and Categorical features encoded. 
Model Building: In this step, the first dataset Splitting is done. After that model is trained on different Machine Learning Algorithms such as:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Reressor
Model Selection: Tested all the models to check the RMSE, R-squared, and Cross-Validation Score.

Pickle File: Selected model per best RMSE score, R-squared, Cross Validation Score and created pickle file using pickle library.
