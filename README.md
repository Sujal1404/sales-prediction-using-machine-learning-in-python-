# sales-prediction-using-machine-learning-in-python-

📌 Project Overview

The Sales Prediction Using Machine Learning project focuses on predicting future sales based on historical advertising and marketing data. Businesses can use such predictions to optimize marketing strategies and improve revenue generation.

In this project, machine learning algorithms are applied to analyze the relationship between advertising budgets (TV, Radio, Newspaper) and sales performance to build an accurate predictive model.

The project demonstrates a complete data science workflow including data preprocessing, exploratory data analysis (EDA), model building, and performance evaluation.

🎯 Project Objectives

Analyze historical advertising data to understand sales trends

Perform data cleaning and preprocessing

Conduct exploratory data analysis (EDA)

Build a machine learning regression model

Evaluate the model’s predictive performance

📂 Dataset

The dataset contains advertising spending across different channels and corresponding sales results.

Feature	Description
TV	Advertising budget spent on TV
Radio	Advertising budget spent on Radio
Newspaper	Advertising budget spent on Newspaper
Sales	Product sales (target variable)

This dataset is commonly used for marketing analytics and sales forecasting projects.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

📊 Exploratory Data Analysis (EDA)

EDA was conducted to understand the relationship between advertising channels and sales.

Key analysis includes:

Sales distribution analysis

Correlation between advertising channels and sales

Scatter plots for feature relationships

Correlation heatmap visualization

Important insight:
TV advertising shows a strong positive correlation with sales compared to other channels.

⚙️ Machine Learning Workflow

1️⃣ Data Loading
2️⃣ Data Cleaning
3️⃣ Exploratory Data Analysis
4️⃣ Feature Selection
5️⃣ Train-Test Split
6️⃣ Model Training
7️⃣ Model Evaluation

🤖 Model Used

The project uses Regression Algorithms to predict sales.

Models implemented:

Linear Regression

Random Forest Regressor

Decision Tree Regressor

📈 Model Evaluation

Model performance was evaluated using the following metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

The trained model successfully predicts sales with good accuracy using advertising budget features.

📊 Example Prediction

Input Advertising Budget:

TV: 150
Radio: 25
Newspaper: 15

Predicted Sales:

Sales ≈ 16.8 units

📁 Project Structure
sales-prediction-using-machine-learning-in-python
│
├── dataset
│   └── advertising.csv
│
├── notebooks
│   └── sales_prediction.ipynb
│
├── images
│   └── visualizations.png
│
├── requirements.txt
│
└── README.md
