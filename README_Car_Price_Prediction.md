# Car Price Prediction using Decision Tree Regressor

## Project Overview

This project predicts the selling price of a car using a Decision Tree
Regressor.

## Libraries

-   pandas
-   numpy
-   matplotlib
-   scikit-learn
-   pickle

## Code Explanation

### Import Libraries

Imports all required libraries for data processing, visualization,
machine learning, evaluation, and model saving.

### Load Dataset

Reads the CSV dataset using `pd.read_csv()`.

### Data Exploration

-   `head()` displays first rows.
-   `info()` shows data types.
-   `describe()` shows statistics.
-   `isnull().sum()` checks missing values.

### Label Encoding

Converts categorical columns (Car_Name, Fuel_Type, Seller_Type,
Transmission) into numerical values.

### Feature Selection

`X` contains all input features. `y` contains `Selling_Price`.

### Train-Test Split

Splits the dataset into 80% training and 20% testing data.

### Model Training

Creates a `DecisionTreeRegressor` and trains it using `fit()`.

### Prediction

Uses `predict()` to estimate selling prices.

### Evaluation

-   R² Score
-   MAE
-   MSE
-   RMSE

### Plot Tree

Uses `plot_tree()` to visualize the trained decision tree.

### Save Model

Stores the trained model as `car_price_model.pkl`.

## Workflow

1.  Import libraries
2.  Load dataset
3.  Explore data
4.  Encode categorical columns
5.  Split features and target
6.  Train-test split
7.  Train Decision Tree Regressor
8.  Predict
9.  Evaluate
10. Plot decision tree
11. Save model
