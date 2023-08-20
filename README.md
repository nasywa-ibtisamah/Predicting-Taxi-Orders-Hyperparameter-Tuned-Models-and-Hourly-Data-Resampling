# Project Description

Hello there :wave:
I hope this project finds you well!

In this project, I will compare four models to determine which one has the lowest RMSE value along with the fastest processing time. These models are utilized to estimate the market value of cars using gradient descent techniques.


**Objective**

Training the gradient descent model and performing hyperparameter tuning using the Root Mean Square Error (RMSE) metric to evaluate the model.

**Used Model**
1. Linear Regression Model
2. Decision Tree Regressor Model
3. Random Forest Regressor Model

# Steps

1. Data Overview
2. Data preprocessing
3. Model Training and Evaluation
4. Testing the Model on Test Set

## 1. Data Overview


**Features:**

-   `datetime` - date and time

**Target:**

-   `num_orders` - number of orders

**Conclusion of Data Exploration Stage**

1. The "parse_dates" argument has been added during the dataset loading stage to convert the Dtype from object to datetime.
2. There are no missing values in both columns.
3. The historical data starts from March 1, 2018, and goes up to August 31, 2018.

## 2. Data Preprocessing

The following are data preprocessing steps I did in this project:
1. Data Resampling
2. Features Engineering

## 3. Model Training and Evaluation

**Analysis Result**

From the testing results on features_train and features_set using three models (Linear Regression, Decision Tree Regressor, and Random Forest), the best result is obtained using the Linear Regression model.

## 3. Testing the Model on Test Set

The RMSE value for train set = 28.99
The RMSE value for test set = 47.89

# General Conclusion

From the testing results on features_train and features_set using three models (Linear Regression, Decision Tree Regressor, and Random Forest), the best result is obtained using the Linear Regression model. The RMSE value for train set and Test set
