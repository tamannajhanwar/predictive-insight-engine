# 🏡 Real Estate House Price Prediction

## 📌 Project Overview

This project focuses on predicting house prices using Machine Learning Regression Algorithms. Different models are implemented and compared to identify the best-performing model.

## 🎯 Objectives

* Understand and implement supervised learning algorithms.
* Build different regression models.
* Evaluate model performance using different metrics.
* Identify overfitting and underfitting.
* Compare models and select the best-performing model.

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* SciPy
* Jupyter Notebook

## 📊 Dataset

The dataset contains real estate information such as:

* Area (sqft)
* Bedrooms
* Bathrooms
* Location Score
* Age of Property
* Distance from City
* Lot Size
* Garage Availability
* Swimming Pool Availability
* Renovation Details

**Target Variable:** House Price (INR)

## 🤖 Machine Learning Models Implemented

1. **Simple Linear Regression:** Predicts house prices using one independent variable (area).

2. **Multiple Linear Regression:** Predicts house prices using multiple independent variables.

3. **Polynomial Regression:** Captures non-linear relationships between features and house prices.

4. **Stochastic Gradient Descent (SGD):** Uses gradient descent optimization to minimize prediction errors.

## 📈 Model Performance Comparison

| Model                      |        MAE |       RMSE | R² Score |
| -------------------------- | ---------: | ---------: | -------: |
| Simple Linear Regression   | 6294593.70 | 8184696.70 |   0.5625 |
| Multiple Linear Regression | 2605648.61 | 3549256.56 |   0.9177 |
| Polynomial Regression      | 1659159.31 | 2262740.88 |   0.9666 |
| SGD Regression             | 2636558.82 | 3581058.54 |   0.9163 |

## 🏆 Best Performing Model

Polynomial Regression performed the best with an R² score of **0.9666** and the lowest prediction errors.

It explains approximately 96.66% of the variation in house prices.

## 🔍 Model Evaluation

* Simple Linear Regression shows underfitting.
* Multiple Linear Regression provides a good fit.
* Polynomial Regression provides the best performance with no significant evidence of overfitting.
* SGD Regression achieves good predictive performance through optimization.

## 💼 Business Interpretation

House price prediction can help real estate companies estimate property values, assist buyers in making purchasing decisions, and support investors in identifying potential investment opportunities.

Polynomial Regression provides the most accurate predictions among the models tested.

## 📌 Conclusion

This project demonstrates the application of Machine Learning in real estate price prediction. After comparing different regression algorithms, Polynomial Regression achieved the best performance with an R² score of 0.9666.

The project helped develop practical knowledge of regression algorithms, model evaluation, optimization, and predictive analytics.
