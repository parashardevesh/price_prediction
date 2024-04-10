# Stock Price Prediction with Machine Learning

- This project focuses on predicting Apple's stock price using Machine Learning techniques like Linear Regression and Decision Tree Regression. The aim is to forecast the stock price for the next 25 days based on historical data.

## Dataset
- The dataset used in this project contains historical stock price data of Apple. It was obtained from Kaggle and covers a period of 10 years. However, for this project, I have focused on the years 2019 and 2020.

## Steps
- **Data Import and Exploration**: The dataset was imported using the Pandas library, and initial exploration was conducted to understand its structure and features.

- **Data Visualization**: The Close Price data was visualized using Matplotlib and Seaborn to gain insights into the stock price trends over time.

  ![apple_stock.png](/assets/apple_stock.png)

- **Data Preprocessing**: Features were selected and the dataset was prepared for training the models. This involved creating a target column by shifting the Close Price values to predict future prices.

- **Model Building**: Two Machine Learning models were implemented - Decision Tree Regression and Linear Regression. The dataset was split into training(80%) and testing(20%) sets, and the models were trained on the training data.

- **Prediction**: The trained models were used to predict the stock prices for the next 25 days.

- **Model Evaluation**: The predictions were visualized alongside the actual stock prices to evaluate the performance of the models.

  ![linear_regression_price_prediction](/assets/linear_regression_price_prediction.png)

  ![tree_regression_price_prediction](/assets/tree_regression_price_prediction.png) 

## Results
- The Decision Tree Regression model showed promising results, closely resembling the actual behaviorr of the stock price over the next 25 days. On the other hand, the predictions made by the Linear Regression model were not as accurate, indicating a need for further refinement or exploration of alternative models.

## Conclusion
- This project demonstrates the application of Machine Learning in predicting stock prices using historical data. By analyzing and understanding the trends, investors can make informed decisions about buying or selling stocks.
