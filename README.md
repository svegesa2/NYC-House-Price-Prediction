# New York House Price Prediction - by SANJANA VEGESANA

## Overview 
This project applies machine learning techniques to predict house prices in New York. It features several models to tackle both regression and classification tasks:

Regression Models predict the actual prices of houses.
Classification Models categorize houses into two classes based on whether they are above or below the median price.
An optional Clustering Analysis identifies distinct groups or patterns within the housing data.
## Models

Linear Regression: Used to establish a baseline for price prediction based on linear relationships between features.
Decision Tree: Provides a non-linear approach that might capture more complex patterns in the data.
Random Forest Classifier: Classifies houses based on a variety of features, using an ensemble of decision trees to improve prediction accuracy and robustness.
Support Vector Machine (SVM): Employs a kernel method to classify houses, ideal for handling non-linear data separation.
K-Means Clustering (Optional): Groups houses into clusters to identify underlying patterns or similarities in the dataset.
## Metrics

Regression Metrics: Mean Squared Error (MSE) and R² score.
Classification Metrics: Accuracy, Precision, Recall, and F1-Score.
Clustering Metrics (if used): Silhouette Score.
## Dataset 

The dataset includes features such as the number of bedrooms, bathrooms, square footage, type of house, and geographical coordinates. Data preprocessing involved handling missing values, encoding categorical variables, and normalizing features where necessary.

## Getting Started

Prerequisites
Ensure you have Python 3.x installed, along with the following packages:
pip install numpy pandas scikit-learn matplotlib seaborn

Running the Models
Navigate to the code directory and run the Python scripts or Jupyter notebooks:

python linear_regression.py

