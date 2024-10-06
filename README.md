# California-Housing-Price-Prediction

[California Housing Price Prediction](https://colab.research.google.com/drive/14ZdowJYA-3K0s1ul06xkPU0sbC-V5Vgl#scrollTo=l2VPJN8iobwT)

This repository contains a machine learning project that predicts house prices in California based on various features such as income, house age, and location. The project uses an XGBoost Regressor to perform the prediction task.


Table of Contents
Introduction
Dataset
Usage
Model
Results


Introduction
The goal of this project is to predict the housing prices in California using the California Housing Dataset. The dataset includes features like average income, house age, average rooms per household, and more. The prediction model is built using the XGBoost Regressor algorithm, a powerful gradient boosting technique.

Dataset
The dataset used is the California Housing Dataset, which is available through the sklearn.datasets module. It contains various features such as:

MedInc: Median income in block group
HouseAge: Median house age in block group
AveRooms: Average number of rooms per household
AveOccup: Average number of people per household
Latitude/Longitude: Geographical coordinates
This dataset can be fetched directly using the fetch_california_housing() function from sklearn.datasets.


The script will:

Load the California Housing dataset using sklearn.datasets.fetch_california_housing.
Split the dataset into training and testing sets.
Train an XGBoost Regressor on the training data.
Evaluate the model on the test data using various regression metrics.
Model
This project uses the XGBoost Regressor to predict house prices. Below are the main steps:

Data Splitting: The dataset is split into training and testing sets using train_test_split.
Model Training: The XGBoost Regressor model is trained using the training data.
Model Evaluation: The model’s performance is evaluated using regression metrics such as Mean Absolute Error (MAE) and R-squared (R²).
Key Libraries Used:
pandas for data manipulation.
numpy for numerical operations.
matplotlib and seaborn for data visualization.
scikit-learn for data splitting and evaluation metrics.
xgboost for implementing the gradient boosting regression model.
