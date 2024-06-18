# Car_Price_Prediction-
Used Car Price Prediction | XGBoost | Python | Plotly | Machine Learning

## Object
To predict the prices of used cars using various regression algorithms in Python, including Linear Regression, Decision Tree Regression, Random Forest Regression, and XGBoost Regression, we'll use the MSRP (Manufacturer's Suggested Retail Price) as the target variable. Let's structure our project report for GitHub, focusing on the implementation details and results of each model.

## Introduction
The goal of this project is to predict the prices of used cars based on various features using machine learning regression algorithms. We will compare the performance of different algorithms and utilize Plotly for visualization.

## Dataset
The dataset used contains the following columns:

Features: 'Make', 'Model', 'Type', 'Origin', 'DriveTrain', 'EngineSize', 'Cylinders', 'Horsepower', 'MPG_City', 'MPG_Highway', 'Weight', 'Wheelbase', 'Length'
Target: 'MSRP' (Manufacturer's Suggested Retail Price)
Methodology
## Data Preprocessing:

Handling missing values.
Encoding categorical variables.
Splitting data into training and testing sets.

## Model Building:
Linear Regression: A simple baseline model.
Decision Tree Regression: Captures non-linear relationships.
Random Forest Regression: Ensemble of decision trees for improved accuracy.
XGBoost Regression: Gradient boosting algorithm for better performance.

## Model Evaluation:
Metrics used: R-squared (coefficient of determination).
Visualization: Using Plotly for interactive scatter plots to visualize predicted vs actual prices.
Results
Linear Regression: Achieved an R-squared of 63%, indicating moderate predictive power.
Decision Tree Regression: Attained an R-squared of 58%, demonstrating weaker performance due to overfitting.
Random Forest Regression: Outperformed with an R-squared of 80%, showing robustness against overfitting.
XGBoost Regression: Achieved an R-squared of 79%, proving effective in predicting car prices.

## Conclusion
Random Forest and XGBoost regressors outperformed Linear Regression and Decision Tree Regression, with Random Forest showing the highest accuracy.
These models can assist in predicting used car prices based on various attributes, aiding in pricing strategies for sellers and providing guidance to buyers.

## Future Improvements
Fine-tuning model hyperparameters for better performance.
Exploring additional features or advanced feature engineering techniques.
Evaluating model robustness over different time periods or geographical regions.
