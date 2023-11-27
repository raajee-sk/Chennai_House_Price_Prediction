# Chennai House price Prediction



## Introduction
This project aims to develop two machine learning models for house price prediction in Chennai to address the challenges of predicting sales price.Manual predictions can be time-consuming and may not result in optimal pricing prediction. The models will utilize advanced techniques such as data normalization, outlier detection and handling, handling data in the wrong format, identifying the distribution of features, and using all Regression model and select the model of  better accuracy score.specifically RandomForestRegressor Model is used to predict the sales price of house.

## Regression model details
The house price  deals with less complex data related to sales and pricing. However, this data may suffer from issues such as skewness and noisy data, which can affect the accuracy of manual predictions. Dealing with these challenges manually can be time-consuming and may not result in optimal pricing prediction. A machine learning regression model can address these issues by utilizing advanced techniques such as data normalization, outlier detection and handling, handling data in wrong format, identifying the distribution of features, and leveraging regression, specifically the RamdomForestRegressor.


## Solution

The solution includes the following steps:

Exploring skewness and outliers in the dataset.

Transforming the data into a suitable format and performing any necessary cleaning and pre-processing steps.

Developing a machine learning regression model which predicts the continuous variable 'Sales_Price' using the RandomForest regressor.

Creating a Streamlit page where you can insert each column value and get the Sales_Price predicted value of house.

## Requirements

This project requires the following libraries to be installed:

NumPy

Pandas

Scikit-learn

Streamlit

## Getting Started


Install the required libraries.

Run the Streamlit app using the command: streamlit run app.py.

Enter the values for each column to get the Sales_Price predicted value of house.
