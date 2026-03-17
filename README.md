# House Price Prediction

## Project Overview

Predicting house prices is a common regression problem in data science and an important task in the real estate industry. Accurate price prediction can help buyers, sellers, and investors make better decisions.

This project builds machine learning models to estimate house prices based on property characteristics. The analysis includes data exploration, feature selection, and model comparison to evaluate different predictive approaches.

The project demonstrates a typical supervised learning workflow for a regression problem using Python and popular machine learning libraries.

---

## Dataset

The dataset contains information about residential properties and their corresponding sale prices.

Typical features included in the dataset:

- property size
- number of bedrooms and bathrooms
- location-related attributes
- building characteristics
- other structural and quality indicators

The target variable is **house price**, which the models attempt to predict.

---

## Business Objective

Accurate house price estimation can support several real-world applications:

- real estate market analysis
- property valuation
- investment decision-making
- automated pricing tools for real estate platforms

The objective of this project is to build predictive models that estimate property prices using historical housing data.

---

## Methodology

The project follows a structured machine learning pipeline:

### 1. Data Exploration
Initial inspection of the dataset to understand variable distributions and relationships with house prices.

### 2. Data Cleaning
Handling missing values, correcting data types, and preparing the dataset for modeling.

### 3. Feature Selection
Identifying the most relevant features that influence house prices.

### 4. Exploratory Data Analysis (EDA)
Visualizing relationships between variables such as:

- house size
- number of rooms
- property characteristics
- price distribution

### 5. Model Training
Two regression models are trained and compared:

- Linear Regression
- Random Forest Regressor

### 6. Model Evaluation
Model performance is evaluated using regression metrics and prediction comparisons.

---

## Models

### Linear Regression

Used as a baseline regression model to estimate house prices based on linear relationships between features and the target variable.

### Random Forest Regressor

A tree-based ensemble model capable of capturing more complex and non-linear relationships between property features and housing prices.

---

## Results

The models are evaluated and compared to determine which approach provides more accurate price predictions.

Random Forest generally performs better than linear regression because it can capture complex interactions between housing features.

---

## Technologies Used

The project is implemented using the following tools:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Author

Costanza Pizzi
