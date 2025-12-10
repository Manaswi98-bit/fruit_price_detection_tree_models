# fruit_price_detection_tree_models
Predicting the price of fruits using regression algorithms based on their physical and quality attributes.

📌 Project Overview

This project builds a Machine Learning regression model that predicts the price of fruits based on multiple characteristics such as size, weight, sweetness, crunchiness, juiciness, ripeness, and acidity.
It is aimed at helping retailers, vendors, and supply-chain systems estimate fruit prices more accurately using data-driven methods.

The model is trained using a Decision Tree Regressor, selected after comparing multiple algorithms such as Linear Regression, SVR, and tuned Decision Trees.

The final model achieved strong performance with:

✔ High R² Score

✔ Low MAE & RMSE

✔ Good generalization on test data

📂 Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-Learn

Decision Tree Regression

🧠 Machine Learning Workflow

Data Loading & Cleaning

Handling missing values

Data type correction

Outlier analysis

Exploratory Data Analysis (EDA)

Distribution plots

Correlation heatmap

Feature relationships

Feature Engineering

Scaling (if required)

Label encoding (if categorical features exist)

Model Training & Evaluation
Models tested:

Linear Regression

SVR

Decision Tree Regressor

Final model used: Decision Tree Regressor (tuned)

Model Saving

Model saved using joblib.dump()

Model Deployment with Flask

REST API created to make predictions

/predict endpoint accepts JSON input

Returns predicted fruit price

🎯 Project Goals

Build an accurate fruit price prediction model

Compare ML algorithms & choose best performer

Deploy the model through a real-time API

Showcase end-to-end ML engineering skills
