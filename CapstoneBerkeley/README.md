## Stock Sector Performance Prediction Using Economic Indicators

**Author: Romi Ban**


### Project Overview

This project explores the relationship between economic indicators and the performance of three major stock market sectors: Technology (XLK), Healthcare (XLV), and Energy (XLE). The goal is to predict whether the "close" price of each sector will go up or down based on various economic indicators such as GDP growth, interest rates, inflation, and unemployment. By using machine learning techniques like classification with Random Forest models, this project aims to determine how well these economic factors can predict stock sector movements.

### Data

The datasets used in this project includes both stock market data and economic indicators to explore their impact on the performance of different stock sectors. The following data sources were used:

#### Stock Market Data:
•	XLK (Technology ETF): Daily prices from 1988-12-23 to 2024-08-23, covering the technology sector.<br>
•	XLV (Healthcare ETF): Daily prices from 1988-12-23 to 2024-08-23, covering the healthcare sector.<br>
•	XLE (Energy ETF): Daily prices from 1988-12-23 to 2024-08-23, covering the energy sector.<br>

#### Economic Indicators:
•	GDP Growth Rate: Data from 1947-01-01 to 2024-04-01, reflecting the overall economic activity.<br>
•	Federal Interest Rates: Data from 1954-07-01 to 2024-07-01, representing the federal interest rate.<br>
•	Inflation Rate: Data from 1960-01-01 to 2023-01-01, representing the inflation rate.<br>
•	Unemployment Rate: Data from 1948-01-01 to 2024-07-01, reflecting employment conditions.<br>
•	Consumer Confidence Index: Data from 1960-01-01 to 2024-01-01, measuring consumer sentiment.<br>
•	Retail Sales: Data from 1992-01-01 to 2024-07-01, representing consumer spending patterns.<br>
•	Industrial Production Index: Data from 1919-01-01 to 2024-07-01, tracking industrial output.<br>
•	Crude Oil Sales: Data from 1990-01-01 to 2024-06-01, tracking crude oil prices.<br>
•	10-Year Treasury Yield: Data from 1962-01-02 to 2024-08-26, representing long-term interest rates.<br>

These datasets were combined into a dataset, with the stock prices serving as the target variable and the economic indicators as features. This allowed me to explore of how various economic factors influence sector performance.

#### Methodology
The project was carried out in several key steps:
1.	Data Preprocessing: The stock price data was aligned with the economic indicators, handling any missing or non-numeric data.
2.	Classification Modeling: A Random Forest classifier was trained to predict whether stock prices would rise or fall based on the economic data.
3.	Hyperparameter Tuning: Grid Search and cross-validation were used to identify the best model configuration.
4.	Model Evaluation: The model's performance was evaluated using metrics like accuracy, precision, recall, and F1-score.

### Results

Despite extensive model tuning, the classification models had limited predictive power, with cross-validation accuracy scores ranging between 45% and 50% across the sectors. This performance is only slightly better than random guessing, indicating that the current economic indicators alone may not be sufficient to predict short-term stock price movements.

### Conclusion

The analysis shows that while factors like GDP, interest rates, and unemployment do have some influence on stock performance, they are not strong predictors of short-term price movements. Short term stock performance, is likely influenced by a wider array of factors that are not captured in this analysis, such as sector-specific trends or technical market data.

## Next Steps

Future work could involve:

•	Including Technical Indicators: Incorporating technical stock indicators (e.g., moving averages, RSI) may better capture short-term market movements.<br>
•	Experimenting with Neural Networks: Using neural networks, such as Long Short-Term Memory (LSTM) models, could be beneficial in capturing temporary patterns in stock data and better predicting price movements over time.<br>

