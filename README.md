# Paris_Housing_Price_Prediction

### Overview

Aim of the project is to predict house prices in Paris using supervised learning techniques. The dataset contains 10,000 entries with 17 attributes, including property size, number of rooms, additional features, and location information. The goal is to develop accurate models for real estate price estimation to assist buyers in making informed decisions.

### Dataset

Source: Kaggle.

Attributes:

1. Numerical: Property size (sqm), number of rooms, number of previous owners, number of floors, basement size, attic size, garage size.

2. Categorical/Binary: Presence of a yard, pool, storm protection, storage room, guest room, and whether the property is newly built.

3. Target Variable: Property price

### Problem Statement

The objective of this project is to predict real estate prices based on various property characteristics. Reliable price estimation is essential for:

- Better Decision-Making: Buyers and sellers can determine fair property prices.

- Investment Strategy: Real estate investors can analyze trends and make profitable investments.

- Market Transparency: Reducing uncertainty and speculation in the housing market.

- Urban Planning & Policy Making: Government agencies can use the data for infrastructure and housing policies.

### Methodology

Data Preparation

- Outlier detection was performed using box plots, and no significant outliers were found.

- Correlation analysis was conducted using a heatmap to identify key influencing features.

Modeling

The following supervised learning regression algorithms were tested:

- Linear Regression (Best Model, Error: 1497.56)

- Random Forest Regressor (Error: 3081.43)

- K-Neighbors Regressor (Error: 20847.67)

- XGBoost Regressor (Worst Model, Error: 2,506,004.72)

### Tools & Technologies

Data Processing & Visualization: Jupyter Notebook, MLOS software, Heatmaps, Box Plots

Machine Learning Algorithms: Linear Regression, Random Forest, K-Neighbors, XGBoost

Evaluation Metrics: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)

### Results & Insights

Linear Regression performed the best, showing the lowest error, making it the most accurate model for this dataset.

Random Forest Regressor was the second-best performing model, though with slightly higher errors.

K-Neighbors Regressor and XGBoost Regressor had significantly higher errors, making them less suitable for this dataset.

### Future Improvements

- Hyperparameter tuning to optimize model performance.

- Feature engineering to enhance predictive power.

- Exploring advanced models such as Gradient Boosting or Neural Networks.

- Cross-validation and error analysis to improve model robustness.

### Conclusion

This project provides an effective way to predict house prices in Paris, helping buyers make data-driven decisions. The model can be further refined with improved feature selection and tuning for better accuracy.
