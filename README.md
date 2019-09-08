# House-Prices-Advanced-Regression-Techniques
This repository contains the solution of the House Prices: Advanced Regression Techniques competition of Kaggle. This contest was undertaken by getting inspired from Google Tech developer guide for Machine Learning (for more info refer: https://techdevguide.withgoogle.com/paths/machine-learning/house-prices-advanced-regression-techniques#!)

# To know more about the competition please follow the link: 
https://www.kaggle.com/c/house-prices-advanced-regression-techniques

# Install:

## To execute the Python Script
I am using Python 3.6.1 for this project. You need to install the following libraries.
1. NumPy (for documentation:http://www.numpy.org/)
2. Pandas (for documentation:http://pandas.pydata.org/)
3. Scikit-Learn (for documentation:http://scikit-learn.org/stable/)
4. XGBoost (for documentation:http://xgboost.readthedocs.io/en/latest/model.html)

## To execute the R Script
I am using R 3.4.4 for this project. You need to install the following libraries.
1. e1071 (to check for skewness)
2. stringr (for locating the NA rows of all the basement features)
3. dplyr, magrittr (data transformation)
4. ggplot2 (plots)
6. scales (Graphical scales map data to aesthetics, and provide methods for automatically determining breaks and labels for axes and legends)
7. corrplot (for Correlation plot)
8. GGally (Extension to ggplot2 for correlation matrix and survival plots)
9. moments, psych (to check for normality of independent variable and standardizing the independent variables)

# Code:
The code contains in the 'Predict-House-Prices.py' & 'Predict-House-Prices.R' file.

# Data:
The training data contains in 'train.csv' file and the testing data contains in the 'train.csv' file and the testing data contains in the 'test.csv' file. I am also adding a file 'Data Description.txt' which contains the explanations of the fields available in the other data files.

#To download the data please follow the links:
1. train.csv (https://www.kaggle.com/c/house-prices-advanced-regression-techniques/download/train.csv)
2. test.csv (https://www.kaggle.com/c/house-prices-advanced-regression-techniques/download/test.csv)

# Goal:
The goal for the competition is to predict the sales price for each house. For each Id in the test set, you must predict the value of the SalePrice variable. 
