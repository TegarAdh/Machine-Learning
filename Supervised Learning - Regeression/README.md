# Supervised Learning - Regression

## Overview
> This project is part of a Machine Learning study focusing on Supervised Learning, specifically Regression models.
> Supervised learning is a machine learning approach where models learn from labeled data (input-output pairs) to make predictions on unseen data .
In this project, regression is used to predict continuous values, such as housing prices.

## Objectives
* Understand the concept of regression in machine learning
* Implement regression using real-world dataset
* Evaluate model performance using standard metrics
* Visualize relationships between variables

## Dataset
### Dataset used:

* USA Housing Dataset

### Features:

* Avg. Area Income
* Avg. Area House Age
* Avg. Area Number of Rooms
* Avg. Area Number of Bedrooms
* Area Population

### Target:

* Price (House Price)

## Concepts Covered

* Supervised Learning
* Regression
* Data Preprocessing
* Train-Test Split
* Model Training
* Model Evaluation

Regression itself aims to learn a function that maps input features to a continuous output value

## Tools & Libraries

* Python 
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## Implementation
### 1. Data Preprocessing

* Load dataset
* Check missing values
* Feature selection

### 2. Train-Test Split

```python
from sklearn.model_selection import train_test_split

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.3)
```

### 3. Model Training (Linear Regression)

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)
```

### 4. Prediction

```python
predictions = model.predict(X_test)
```

## Evaluation Metrics

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

## Visualization

* Scatter Plot (Actual vs Prediction)
* Residual Plot
* Distribution Plot

## Project Structure

```
Supervised Learning - Regression/
│
├── USA_Housing.csv
├── Supervised_Learning_Hands_On_Regresi.ipynb
├── Regression.pdf
├── README.md
```

## References

* Machine Learning Fundamentals
* Scikit-learn Documentation
* Regression Concepts

## Author

[![GitHub](https://img.shields.io/badge/GitHub-TegarAdh-black?logo=github)](https://github.com/TegarAdh)

## Future Improvements

* Feature Engineering
* Hyperparameter Tuning
* Model Comparison (Decision Tree, Random Forest)
* Cross Validation
