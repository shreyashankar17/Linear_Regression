Linear Regression Project: Predicting Sales from Advertising Data
What is Linear Regression?
Linear regression is a simple yet powerful statistical method used to model the relationship between a dependent variable (target) and one or more independent variables (features). The model assumes a linear relationship between the variables, meaning that the change in the target variable is proportional to the change in the independent variables.

The linear regression model can be represented by the equation:

Sales = 𝛽 0 + 𝛽 1 ( TV ) + 𝛽 2 ( Radio ) + 𝛽 3 ( Newspaper ) + 𝜖 Sales=β 0​+β 1​(TV)+β 2​(Radio)+β 3​(Newspaper)+ϵ

Where: β 0​is the intercept, 𝛽 1 , 𝛽 2 , 𝛽 3 β 1​,β 2​,β 3​are the coefficients for each independent variable,

ϵ is the error term. Linear regression is widely used for predictive analysis, allowing us to understand the impact of different features on the target variable and to make predictions for new data.

Project Overview
This project involves building a linear regression model using an advertising dataset. The dataset contains information on TV, Radio, and Newspaper advertising expenditures and the corresponding sales figures. The goal of the project is to predict sales based on the advertising budgets.

Dataset
The dataset consists of 200 observations, each containing the following columns:

TV: Advertising budget spent on TV (in thousands of dollars)

Radio: Advertising budget spent on Radio (in thousands of dollars)

Newspaper: Advertising budget spent on Newspaper (in thousands of dollars)

Sales: Sales of the product (in thousands of units)

Project Approach
Data Exploration:
Loaded the dataset and performed basic exploratory data analysis (EDA) to understand the relationships between variables.

Data Preprocessing:
Checked for missing values and outliers. Scaled the features if necessary.

Model Building:
Split the data into training and testing sets. Built a linear regression model using the training set. Evaluated the model's performance on the testing set.

Model Evaluation:
Calculated performance metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared to evaluate the model.

Role of Linear Regression in This Project
In this project, linear regression is used to model and predict the Sales based on three independent variables: TV, Radio, and Newspaper advertising budgets. The goal is to understand how these advertising expenditures influence sales and to create a model that can predict future sales based on new advertising data.

By applying linear regression, we aim to:

Identify the strength and direction of the relationship between each type of advertising and sales. Determine which advertising medium has the most significant impact on sales. Build a predictive model that can be used to forecast sales based on different advertising budgets. The linear regression model helps in quantifying the contribution of each advertising channel to sales, providing valuable insights for optimizing marketing strategies.
