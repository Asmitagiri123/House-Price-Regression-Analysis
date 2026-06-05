# Regression Analysis using Python (Linear Regression)

## Project Overview

This project demonstrates a simple linear regression analysis using Python and scikit-learn. The goal is to predict a dependent variable based on an independent variable using a supervised machine learning approach.

The dataset used in this task is a house price dataset, where the relationship between features such as area and price is analyzed.

---

## Objective

* Perform simple linear regression analysis
* Split dataset into training and testing sets
* Train a linear regression model using scikit-learn
* Predict values on test data
* Evaluate model performance using R² score and Mean Squared Error (MSE)
* Interpret model coefficients

---

## Dataset Description

The dataset contains information related to house prices.

Example columns:

* Area (independent variable)
* Price (dependent variable)

---

## Workflow

### 1. Data Preprocessing

* Loaded dataset using pandas
* Checked for missing values
* Removed or handled missing data (if any)
* Selected relevant features for regression

---

### 2. Feature Selection

* X = Independent variable (Area)
* y = Dependent variable (Price)

---

### 3. Train-Test Split

* Dataset split into training and testing sets
* 80% data used for training
* 20% data used for testing

---

### 4. Model Training

* Applied Linear Regression using scikit-learn
* Model learned relationship between area and price

---

### 5. Prediction

* Used trained model to predict values on test data

---

### 6. Model Evaluation

The model was evaluated using:

* **Mean Squared Error (MSE):** Measures average squared difference between actual and predicted values
* **R² Score:** Measures how well the model explains variation in the data

---

## Model Interpretation

* Coefficient represents how much the target variable changes with respect to the independent variable
* Intercept represents the base value when the independent variable is zero
* Final equation:
  **Price = (Coefficient × Area) + Intercept**

---

## Tools Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Google Colab

---

## Conclusion

This project helped in understanding the basics of linear regression, model training, prediction, and evaluation. It also provided practical exposure to supervised machine learning workflow using Python.

---

## Author

Asmita Giri
