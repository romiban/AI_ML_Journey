## Stock Sector Performance Prediction Using Economic Indicators

### Project Overview

This project analyzes the relationship between economic conditions and the performance of three major stock market sectors: Technology (XLK), Healthcare (XLV), and Energy (XLE). Using classification techniques and Random Forest models, I attempt to predict whether the "close" price for each sector will go up or down based on various economic indicators such as GDP growth, interest rates, inflation, and unemployment. The goal is to explore how well these macroeconomic factors can predict stock sector movements.

### Data

I used daily stock data for XLK, XLV, and XLE ETFs from Yahoo Finance, combined with economic indicators sourced from public datasets. Key features used include:

GDP Growth Rate
Federal Interest Rates (FEDFUNDS)
Inflation Rate (FPCPITOTLZGUSA)
Unemployment Rate (UNRATE)
Additional indicators such as Consumer Confidence Index (CCI), Retail Sales, and Industrial Production Index

**Methodology**

The project follows these steps:

Data Preprocessing: Align stock price data with economic indicators, and handle missing or non-numeric data.
Classification Modeling: A Random Forest classifier was used to predict stock movements (up/down) based on economic conditions.
Hyperparameter Tuning: Grid Search and cross-validation were used to find the optimal hyperparameters for the model.
Model Evaluation: The model’s performance was evaluated using cross-validation accuracy and classification reports, with metrics like precision, recall, and F1-score.

### Results

Despite extensive tuning, the classification models achieved limited predictive power, with average cross-validation accuracy scores ranging between 45-50% across sectors, barely above random guessing. This suggests that current economic indicators alone are insufficient to reliably predict short-term stock movements in these sectors.

### Conclusion

The results indicate that while macroeconomic factors influence stock performance, they may not be the sole drivers of short-term price movements. Future work could explore adding sector-specific features or technical indicators to improve model accuracy.
