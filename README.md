Logistic Regression for Titanic Dataset
Overview
This repository contains a project that applies logistic regression to the Titanic dataset to predict survival. The project involves data analysis, visualization, model training, and evaluation. The goal is to build a logistic regression model to classify passengers' survival based on various features.

Project Structure
data/: Contains the Titanic dataset file.
notebooks/: Jupyter notebooks with data analysis, visualization, and model training.
scripts/: Python scripts for data preprocessing, model training, and evaluation.
results/: Generated plots and model evaluation metrics.
Data Analysis
The Titanic dataset is analyzed to understand the distribution of missing values and to visualize the data. Key steps include:

Loading and Cleaning Data: Handling missing values and converting categorical variables.
Visualization: Creating plots to understand data distributions and relationships.
Example Visualization
A heatmap was created to visualize missing values in the dataset:


Model Training
A logistic regression model is trained using the cleaned and preprocessed data. Key steps include:

Splitting Data: Dividing the dataset into training and test sets.
Training the Model: Fitting the logistic regression model to the training data.
Making Predictions: Predicting survival on the test set.