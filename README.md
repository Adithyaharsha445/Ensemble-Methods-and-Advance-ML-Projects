# Ensemble-Methods-in-Machine-Learning

In this project we implement different Ensemble Methods in Machine Learning on wine data. The project is divided into following tasks and the observations are given below:

Task 1: Implement Bagging Bagging Classifier with Decision Tree Classifier as base_estimator gives an accuracy of 75.84%.

Task 2: Bagging Algorithms Random Forest Classifier gives an accuracy of 98%.

Task 3: Implement Boosting ADABoost Classifier with Decision Tree Classifier as base_estimator gives an accuracy of 85.95%.

Task 4: Boosting Algorithms GradiantBoosting and Extreme GB give an accuracy of 88%.

Task 5: Implement Stacking Stacking Classifier gives an accuracy of87%.





# Ensemble-Methods-in-Machine-Learning-if-used-for-Automotive-Industry

Welcome to the ensemble methods models for machine learning. In this document, lets see how bagging, boosting, and stacking work, and see examples applied to automotive data.

## Introduction

Ensemble methods combine multiple models to improve prediction accuracy and reduce errors. They are used widely in various industries, including automotive for tasks like predicting car resale value or classifying vehicle safety.

## Bagging

Bagging stands for Bootstrap Aggregation and involves training multiple models on different samples of the data, then averaging their predictions.

### Real-World Automotive Example: Random Forests

Imagine you're predicting the resale value of cars based on factors like mileage, age, engine size, etc. Random Forests, a type of bagging, build many decision trees (each on a different bootstrapped sample) and average their predictions for better accuracy.

## Boosting

Boosting trains models sequentially where each model learns from the errors of the previous model. Techniques such as AdaBoost and Gradient Boosting fall under this category.

### Real-World Automotive Example: XGBoost

For instance, XGBoost can be used to predict the probability of a car needing maintenance, where each new tree in the ensemble focuses on the errors made by the previous trees.

## Stacking

Stacking involves training multiple diverse models and combining their predictions using a meta-model. This strategy can capture various aspects of the data.

### Real-World Automotive Example: Hybrid Car Sales Forecast

In forecasting car sales, you might combine models like linear regression, decision trees, and neural networks to capture different trends in the data and then use a meta-model to yield the final prediction.
