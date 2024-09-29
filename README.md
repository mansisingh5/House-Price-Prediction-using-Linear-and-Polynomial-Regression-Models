# House-Price-Prediction-using-Linear-and-Polynomial-Regression-Models

The House Price Prediction using Linear Regression project focuses on predicting real estate prices based on various housing features such as square footage, number of bedrooms, bathrooms, and location. The process involves the following key stages:
1. Data Preprocessing and Feature Selection:
The dataset, containing over 21,000 records and 21 columns, is cleaned and prepared by removing irrelevant columns like id and date.
Missing values are handled, and summary statistics are calculated to understand the data distribution.
2. Model Building:
A Linear Regression model is trained to predict house prices based on selected features.
The model's performance is optimized by checking for multicollinearity using the Variance Inflation Factor (VIF), ensuring that highly correlated features are managed.
3. Evaluation and Enhancement:
The model's accuracy is measured using R-squared (0.79) and Mean Squared Error (MSE).
To improve the predictive power, Polynomial Regression is applied to capture non-linear relationships between features and house prices, further refining the model's performance.
