# Linear Regression Project: Predicting Sales from Advertising Data

## What is Linear Regression?
Linear regression is a simple yet powerful statistical method used to model the relationship between a dependent variable (target) and one or more independent variables (features). The model assumes a linear relationship between the variables, meaning that the change in the target variable is proportional to the change in the independent variables.

The linear regression model can be represented by the equation:

Sales =
𝛽
0
+
𝛽
1
(
TV
)
+
𝛽
2
(
Radio
)
+
𝛽
3
(
Newspaper
)
+
𝜖
Sales=β 
0
​
 +β 
1
​
 (TV)+β 
2
​
 (Radio)+β 
3
​
 (Newspaper)+ϵ

Where:
β 
0
​
  is the intercept,
𝛽
1
,
𝛽
2
,
𝛽
3
β 
1
​
 ,β 
2
​
 ,β 
3
are the coefficients for each independent variable, ϵ is the error term.
Linear regression is widely used for predictive analysis, allowing us to understand the impact of different features on the target variable and to make predictions for new data.

## Project Overview
This project involves building a linear regression model using an advertising dataset. The dataset contains information on TV, Radio, and Newspaper advertising expenditures and the corresponding sales figures. The goal of the project is to predict sales based on the advertising budgets.

## Dataset
The dataset consists of 200 observations, each containing the following columns:

TV: Advertising budget spent on TV (in thousands of dollars)

Radio: Advertising budget spent on Radio (in thousands of dollars)

Newspaper: Advertising budget spent on Newspaper (in thousands of dollars)

Sales: Sales of the product (in thousands of units)
## Project Approach
### Data Exploration:

Loaded the dataset and performed basic exploratory data analysis (EDA) to understand the relationships between variables.
### Data Preprocessing:

Checked for missing values and outliers.
Scaled the features if necessary.
### Model Building:

Split the data into training and testing sets.
Built a linear regression model using the training set.
Evaluated the model's performance on the testing set.
### Model Evaluation:

Calculated performance metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared to evaluate the model.

### Role of Linear Regression in This Project
In this project, linear regression is used to model and predict the Sales based on three independent variables: TV, Radio, and Newspaper advertising budgets. The goal is to understand how these advertising expenditures influence sales and to create a model that can predict future sales based on new advertising data.

By applying linear regression, we aim to:

Identify the strength and direction of the relationship between each type of advertising and sales.
Determine which advertising medium has the most significant impact on sales.
Build a predictive model that can be used to forecast sales based on different advertising budgets.
The linear regression model helps in quantifying the contribution of each advertising channel to sales, providing valuable insights for optimizing marketing strategies.

The process begins with loading and exploring the dataset, followed by separating the features and target variable. After splitting the data into training and testing sets, a linear regression model is built and trained. The model's predictions are evaluated using Mean Squared Error (MSE) and R-squared (R²) metrics, with Adjusted R-squared calculated for more accurate performance assessment. This project highlights the key steps in developing and evaluating a linear regression model in machine learning.

## Procedure Steps

#### 1. Importing Libraries:
The necessary libraries are imported, including pandas for data handling, matplotlib.pyplot and seaborn for data visualization, and train_test_split and LinearRegression from sklearn for model building and evaluation.

#### 2. Loading the Dataset:

The dataset is loaded into a pandas DataFrame from a CSV file. It contains data on advertising budgets for TV, Radio, and Newspaper, as well as the corresponding sales figures.

#### 3. Exploratory Data Analysis (EDA):

Data visualization is performed using scatter plots and pair plots to understand the relationships between the features and the target variable (Sales). Correlation analysis is also conducted to assess the strength of these relationships.

#### 4. Data Preprocessing:

The features (TV, Radio, Newspaper) are separated from the target variable (Sales). The data is then split into training and testing sets using train_test_split.

#### 5. Model Building:

A LinearRegression model is instantiated and trained on the training data. The model learns the relationships between the features and the target variable.

#### 6. Making Predictions:

The trained model is used to make predictions on the test data. The predicted sales figures are compared with the actual sales figures to assess model performance.

#### 7. Evaluating Model Performance:

The model's performance is evaluated using metrics like Mean Squared Error (MSE) and R-squared (R²). MSE measures the average squared difference between actual and predicted values, while R² indicates how well the model explains the variance in the data.

#### 8. Adjusting R-squared:

Adjusted R-squared is calculated to account for the number of predictors in the model, providing a more accurate measure of model performance, especially when multiple features are used.




