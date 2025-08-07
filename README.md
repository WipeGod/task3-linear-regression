## Task 3: Linear Regression – House Price Prediction

## Objective
To implement and understand simple and multiple linear regression techniques using the Housing.csv dataset.

## Tools & Libraries
Python
Pandas
NumPy
Matplotlib
Scikit-learn

## Dataset: Housing.csv
This dataset contains information about houses and their features, including:
area, bedrooms, bathrooms, stories, parking, etc.
furnishingstatus: A categorical feature
price: The target variable (house price)

## Steps Performed
1.Loaded the dataset using Pandas.
2.Preprocessed the data:
  One-hot encoded the furnishingstatus categorical column.
3.Split the dataset into training and test sets (80/20).
4.Trained a Linear Regression model using LinearRegression() from scikit-learn.
5.Evaluated the model using:
  Mean Absolute Error (MAE)
  Mean Squared Error (MSE)
  R² Score
6.Visualized the model predictions vs actual prices.
7.Displayed feature importance (coefficients).

## Results
MAE: 970043.40

MSE: 1754318687330.66

R² Score: 0.6529


## Output Plot
  A scatter plot comparing actual vs predicted house prices.
  Ideal predictions lie on the diagonal red dashed line.
