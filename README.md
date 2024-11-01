
# House Price Prediction with Voting Regressor

This project focuses on predicting house prices using various machine learning models combined in a voting regressor. The notebook preprocesses housing data, trains individual models, and then combines them to improve prediction accuracy.

## Table of Contents

Overview
Dataset
Features and Preprocessing
Model Training
Results
Requirements
Usage

## Overview

This project aims to predict house prices based on several factors, such as area, number of bedrooms, bathrooms, and more. By implementing a voting regressor, we leverage the strengths of multiple models to achieve better performance.


## Dataset
The dataset contains features like:

Area
Bedrooms
Bathrooms
Stories
Parking
Furnishing Status
And other binary attributes indicating the presence of amenities like a basement or air conditioning.


## Features and Preprocessing

### Encoding:

Categorical variables, such as furnishing status, are encoded using ordinal encoding.
Binary attributes, like main road access, are label encoded.

### Standardization:

Continuous variables are standardized to ensure models perform optimally.

### Visualization:

The data distribution and correlation heatmap are analyzed to understand relationships between features.


## Model Training
The following machine learning models are trained individually and combined in a voting regressor:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor

The models are evaluated based on metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to gauge accuracy.


## Results

The ensemble voting regressor, which averages predictions from each model, provides a balanced and accurate price prediction.


## Requirements
Install the necessary packages with:
pip install -r requirements.txt


## Main Packages:

numpy
pandas
scikit-learn
matplotlib
seaborn


## Usage

Preprocessing: Load and preprocess the dataset.
Model Training: Run the models individually and then the voting regressor.
Evaluation: Assess the results based on performance metrics.

Run each cell in the provided Jupyter notebook to complete the process.
