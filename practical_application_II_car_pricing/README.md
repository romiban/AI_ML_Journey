Project: Understanding Factors Influencing Used Car Prices
Overview

This project aims to identify the key factors influencing used car prices to assist dealerships in optimizing their inventory selection, pricing strategies, and marketing efforts. By leveraging a comprehensive dataset of 426,000 used car listings, we performed extensive data cleaning, feature engineering, and applied various regression models to gain actionable insights.

Project Workflow

Data Cleaning and Preparation:

Removed irrelevant columns and handled missing values.
Applied transformations to stabilize data variance and reduce skewness.
One-hot encoded categorical variables for better model compatibility.
Feature Engineering:

Created polynomial features to capture non-linear relationships.
Included interaction terms between significant features.
Scaled features to ensure consistency across the dataset.
Model Selection and Evaluation:

Evaluated multiple regression models: Linear Regression, Polynomial Regression, Ridge Regression, and Lasso Regression.
Used Grid Search for hyperparameter tuning and cross-validation to ensure model robustness.
Selected Polynomial Regression with Ridge regularization as the best-performing model based on Mean Absolute Error (MAE) and R-squared (R2) metrics.
Key Findings

Mileage:

Insight: Lower mileage significantly increases car value.
Recommendation: Focus on acquiring vehicles with lower mileage.
Fuel Type:

Insight: Electric cars tend to have higher values compared to gas and hybrid cars.
Recommendation: Stock more electric vehicles.
Title Status:

Insight: Clean titles increase car value, while salvage or rebuilt titles reduce it significantly.
Recommendation: Adjust prices for cars with salvage or rebuilt titles to reflect their lower value.
Car Type:

Insight: Pickups and trucks are more valuable than sedans and hatchbacks.
Recommendation: Increase inventory of pickups and trucks and consider premium pricing for these vehicles.
Recommendations

Inventory Management:

Prioritize acquiring low-mileage vehicles.
Stock a higher proportion of electric vehicles.
Adjust inventory to include more pickups and trucks.
Pricing Strategies:

Implement pricing adjustments for cars with salvage or rebuilt titles.
Apply premium pricing strategies for high-demand car types like pickups and trucks.
Marketing and Sales:

Highlight key features such as low mileage, electric fuel type, and clean title status in marketing campaigns.
Use insights to target specific customer segments based on their preferences.
Next Steps

Further Refinement:

Continue refining the model with additional data and advanced feature engineering techniques.
Validate the model on new data to ensure its robustness and applicability.
Implementation:

Integrate the model into the dealership's inventory and pricing system.
Train the sales and marketing team on using these insights to improve customer engagement and sales performance.
By following these recommendations, the dealership can better meet customer demands, maintain a competitive edge in the market, and improve overall profitability.
