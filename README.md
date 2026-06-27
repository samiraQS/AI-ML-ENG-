# Task 1 – Iris Dataset Exploration

## Task Objective

The objective of this task is to perform Exploratory Data Analysis (EDA) on the Iris dataset. The project focuses on understanding the dataset structure, exploring feature distributions, identifying patterns, and visualizing relationships among different flower species.

## Dataset Used

* **Dataset:** Iris Dataset
* **Source:** Seaborn built-in dataset
* **Features:** Sepal Length, Sepal Width, Petal Length, Petal Width
* **Target Variable:** Species

## Models Applied

No machine learning model was applied in this task. The project focuses on data exploration and visualization using:

* Pandas
* Matplotlib
* Seaborn

## Key Results and Findings

* Successfully loaded and explored the Iris dataset.
* Examined dataset shape, column names, and summary statistics.
* Visualized relationships between features using scatter plots.
* Analyzed feature distributions with histograms.
* Identified variation and potential outliers using box plots.
* Observed clear separation among Iris species based on petal measurements.

 # Task 2 – Stock Price Prediction Using Linear Regression

## Task Objective

The objective of this task is to build a machine learning model that predicts the next day's closing stock price using historical stock market data.

## Dataset Used

* **Dataset:** Apple (AAPL) Historical Stock Data
* **Source:** Yahoo Finance (yfinance)
* **Features:** Open, High, Low, Close, Volume
* **Target Variable:** Next Day Closing Price

## Models Applied

* Linear Regression (Scikit-learn)

## Key Results and Findings

* Downloaded historical Apple stock data using the yfinance library.
* Prepared the dataset by creating the next day's closing price as the target variable.
* Split the data into training and testing sets.
* Trained a Linear Regression model to predict future closing prices.
* Compared actual and predicted stock prices using visualization.
* The model demonstrated that linear regression can capture general price trends, although stock prices remain influenced by many external market factors.


# Task 3 – Heart Disease Prediction

## Task Objective

The objective of this task is to develop a machine learning model that predicts the presence of heart disease based on patient health information and evaluates its performance using standard classification metrics.

## Dataset Used

* **Dataset:** Heart Disease UCI Dataset
* **Source:** UCI Heart Disease Dataset
* **Features:** Patient demographic and clinical attributes (age, cholesterol, blood pressure, chest pain type, etc.)
* **Target Variable:** Heart Disease (num)

## Models Applied

* Logistic Regression (Scikit-learn)

## Key Results and Findings

* Performed data cleaning and preprocessing, including handling missing values and encoding categorical variables.
* Conducted exploratory data analysis using count plots, histograms, and correlation heatmaps.
* Trained a Logistic Regression model on the processed dataset.
* Evaluated the model using accuracy, ROC curve, and confusion matrix.
* Analyzed feature importance using model coefficients to identify variables that contribute most to heart disease prediction.



