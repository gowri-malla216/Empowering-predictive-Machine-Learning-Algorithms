# Model Enhancement Techniques for XGBoost, Decision Trees & Random Forest

This repository contains Jupyter notebooks exploring various model enhancement techniques for XGBoost, Decision Trees, and Random Forest Regressors. The goal is to fine-tune hyperparameters, optimize performance, and compare model efficiencies using RMSE, R² Score, and MSE.

## Techniques Explored
1. Hyperparameter Tuning
  - GridSearchCV – Finding the optimal parameters for Decision Trees & Random Forest
  - Best Alpha Selection – Using Tree Pruning to avoid overfitting
  - Ridge Regression – Reducing overfitting with L2 regularization
  - Ridge Regression with Cross-Validation – Finding the best alpha value dynamically

1. Performance Metrics
  - RMSE (Root Mean Squared Error) – Measures error magnitude
  - R² Score (Coefficient of Determination) – Evaluates model explanatory power
  - MSE (Mean Squared Error) – Measures model variance

## Results & Observations
- GridSearchCV improved Decision Tree and Random Forest performance by selecting optimal parameters
- Tree pruning significantly reduced overfitting in XGBoost
- Ridge Regression improved model generalization, reducing variance
- Cross-validation in Ridge Regression identified the best alpha, preventing over-regularization
