Project Name : RNN_Stock_Price_Prediction

General Information

  - The problem statement for this assignment can be summarised as follows: Given the stock prices of Amazon, Google, IBM, and Microsoft for a set number of days,     predict the stock price of these companies after that window

Background of the project: 

  - The objective of this assignment is to try and predict the stock prices using historical data from four companies IBM (IBM), Google (GOOGL), Amazon (AMZN),         and Microsoft (MSFT).

  - We use four different companies because they belong to the same sector: Technology. Using data from all four companies may improve the performance of the          model. This way, we can capture the broader market sentiment.

Dataset:

  - The dataset consists of four CSV files corresponding to four stocks: AMZN, GOOGL, IBM, and MSFT. The files contain historical data that were gathered from the     websites of the stock markets where these companies are listed: NYSE and NASDAQ.

  - There are more than 3000 records for each company spread across the years. The columns in all four files are identical, which are:

    - Date: The values in this column specify the date on which the values were recorded. In all four files, the dates range from January 1, 2006, to January 1,         2018.
    - Open: The values in this column specify the stock price on a given date when the stock market opens.
    - High: The values in this column specify the highest stock price achieved by a stock on a given date.
    - Low: The values in this column specify the lowest stock price achieved by a stock on a given date.
    - Close: The values in this column specify the stock price on a given date when the stock market closes.
    - Volume: The values in this column specify the total number of shares traded on a given date.
    - Name: This column gives the official name of the stock as used in the stock market.

Conclusions:

  - In this project, we developed and evaluated different recurrent neural network architectures (Simple RNN, LSTM, and GRU) for time series forecasting,              specifically targeting stock closing prices. After careful data preprocessing, windowing, scaling, and model building, we performed extensive hyperparameter       tuning to identify optimal model configurations.

Acknowledgements:

  - This project was inspired by UpGrad IIITB Programme as a case study for the Machine Learning and Artificial Intelligence course.
