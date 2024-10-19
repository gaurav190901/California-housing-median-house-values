# Linear Regression on California Housing Dataset

This project explores **Linear Regression** to predict housing prices using the **California Housing dataset**. It covers data preprocessing, exploratory analysis, model building, and performance evaluation.

## Table of Contents
- [Project Overview](ProjectOverview)
- [Problem Statement](ProblemStatement)
- [Dataset](Dataset)
- [Installation](Installation)
- [Project Structure](ProjectStructure)
- [Usage](Usage)
- [Results](Results)

## Project Overview
In this project, we use the **California Housing dataset** from `scikit-learn` to predict median house prices. This project demonstrates the complete data science workflow:
- **Data preprocessing**: Feature scaling, handling missing values, and preparing data for modeling.
- **Exploratory Data Analysis (EDA)**: Visualizing feature relationships and trends using `Matplotlib`.
- **Modeling**: Building and evaluating a linear regression model using `scikit-learn`.
- **Performance Metrics**: Model performance assessed using **R-squared** and **Mean Squared Error (MSE)**.

## Problem Statement
The goal of this project is to predict the median house value in various districts of California based on several socio-economic and geographical factors. Using the California Housing dataset, this project aims to build a Linear Regression model that accurately predicts house prices, which can help in understanding the key factors influencing real estate prices.

## The project involves:

Analyzing the relationships between housing features (e.g., average income, house age, rooms per household) and house prices.
Building a predictive model using Linear Regression to forecast house prices based on the given features.
Evaluating the model's performance with appropriate metrics like R-squared and Mean Squared Error (MSE) to assess its accuracy and predictive power.
This analysis can provide valuable insights for real estate investors, policymakers, and economists in understanding the housing market in California.

## Dataset
The dataset is the **California Housing dataset**, which contains the following features:
- Median house price (target)
- Average income of residents
- House age
- Average number of rooms, and more.

To fetch the dataset:
```python
from sklearn.datasets import fetch_california_housing
data = fetch_california_housing()
```

## Installation
Clone the repository and install the required dependencies:
git clone https://github.com/gaurav190901/linear_regression_california_housing.git
cd linear_regression_california_housing
pip install -r requirements.txt

## Project Structure
│-- Linear_regression.ipynb      # Main Jupyter notebook with code
│-- README.md                    # Project documentation
│-- requirements.txt             # Python dependencies

## Usage
To run the analysis, open the Jupyter notebook and execute the cells step by step. The notebook includes:

Data loading and preprocessing
Exploratory data analysis (EDA)
Linear regression modeling
Model evaluation with performance metrics

## Results
The linear regression model achieved the following results:

R-squared: Indicates the variance explained by the model.
Mean Squared Error (MSE): Measures the average squared difference between actual and predicted values.
