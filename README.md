# House-Price-Prediction
Project Overview

This project explores house-price prediction using a Linear Regression
model in Python and Scikit-learn. The notebook loads a housing dataset,
inspects and preprocesses the data, encodes selected categorical
features, and trains a regression model to predict SalePrice.

Objectives

Inspect the dataset and understand its structure.

Clean missing values and remove the identifier column.

Convert selected categorical variables into numeric features.

Split the data into training and testing sets.

Train a Linear Regression model to predict sale prices.

Technologies Used

Python

Pandas

Scikit-learn

Jupyter Notebook / JupyterLab

Workflow

Load HousePricePrediction.csv into a Pandas DataFrame.

Inspect the dataset using shape, preview, information, and
descriptive-statistics commands.

Drop the Id column because it is an identifier rather than a
property characteristic.

Fill missing values in SalePrice with the column mean and drop
remaining rows containing missing values.

Apply one-hot encoding with pandas.get_dummies() to the selected
categorical columns:

MSZoning

LotConfig

BldgType

Exterior1st

Split the data into training and testing sets with an 80/20 split
and random_state=0.

Train a LinearRegression model on the training set.

Current Status and Results

The notebook currently demonstrates data inspection, preprocessing,
train-test splitting, and fitting the Linear Regression model. It does
not yet calculate or display test-set evaluation metrics such as
MAE, RMSE, or R². Add these metrics before reporting model accuracy or
making claims about predictive performance.

Files

HousePricingProject.ipynb --- notebook containing the
data-preparation and model-training workflow.

HousePricePrediction.csv --- input dataset required to run the
notebook.

How to Run

Clone or download this repository.

Place HousePricePrediction.csv in the same directory as
HousePricingProject.ipynb.

Install the required libraries:

pip install pandas scikit-learn jupyter

Launch JupyterLab or Jupyter Notebook and run the cells in order.

Notes

The dataset is not included in this README; add it to the repository
only if its licence permits redistribution. Otherwise, provide the
original dataset source.

Before presenting this as a completed predictive model, evaluate it
on the test set and document the results.
