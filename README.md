# Boston House Price Prediction

This repository contains a Python script for predicting house prices in Boston using a Linear Regression model. The code utilizes the famous Boston Housing dataset, which contains various features of houses in Boston and their corresponding prices.

## Dataset

The dataset used for this prediction can be found in `sklearn.datasets` as the Boston Housing dataset. It consists of 506 samples, and each sample has 13 features. The target variable is the median value of owner-occupied homes in $1000s.

Features in the dataset:
- CRIM: per capita crime rate by town
- ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS: proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- NOX: nitric oxides concentration (parts per 10 million)
- RM: average number of rooms per dwelling
- AGE: proportion of owner-occupied units built prior to 1940
- DIS: weighted distances to five Boston employment centers
- RAD: index of accessibility to radial highways
- TAX: full-value property-tax rate per $10,000
- PTRATIO: pupil-teacher ratio by town
- B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- LSTAT: % lower status of the population

Target variable:
- PRICE: median value of owner-occupied homes in $1000s

## Installation

1. Clone the repository to your local machine:

git clone https://github.com/your_username/boston-house-price-prediction.git

2. Ensure you have Python 3 and the required libraries installed:

pip install numpy pandas scikit-learn

# Results

The notebook displays the following information:

-The number of samples in the dataset and a list of features.
-The minimum and maximum prices in the dataset.
-The Mean Squared Error (MSE) and R-squared (R2) values, which are performance metrics of the trained model.
-The predicted price for a new data sample based on the trained model.

# License

This project is licensed under the MIT License - see the LICENSE file for details.

Feel free to use, modify, and distribute this code as permitted by the license.

# Acknowledgments

This project is based on the Boston Housing dataset available in scikit-learn.


