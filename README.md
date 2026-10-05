# Logistic-Regression-From-Scratch
## Diabetes Prediction using Logistic Regression from Scratch 

Developed a binary classification model to predict whether a patient is diabetic or non-diabetic using predictor variables. Implemented and fitted a Logistic Regression model from scratch using gradient descent, with Glucose and BMI as predictors, and visualized the resulting decision boundary.

----

# Project Overview
- Objective: Predict whether a patient is diabetic or non-diabetic using machine learning.
- Dataset: Pima Indians Diabetes dataset containing patient health-related measurements.
- Features selected: Glucose and BMI for building a clear two-dimensional classification model.
- Target variable: label — represents diabetic (1) or non-diabetic (0).
- Model: Logistic Regression implemented from scratch, without using sklearn's built-in logistic regression.
- Model fitting: Used gradient descent to optimize the model parameters by minimizing the logistic log-loss cost function.
- Prediction: Applied the fitted model to classify observations using a 0.5 probability threshold.
- Evaluation: Calculated the training accuracy of the fitted model.
- Visualization: Plotted the two classes based on Glucose and BMI and visualized the linear decision boundary separating the predicted classes.
- Key concepts implemented:
  - Sigmoid function
  - log-loss
  - gradient calculation
  - gradient descent
  - classification
  - decision boundary
