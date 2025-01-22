# Prediction-of-Stock-Price-Direction

# Description
The project aims to predict the price direction of Amazon.com, Inc. (AMZN) stock. Instead of predicting exact stock prices, the focus is on predicting whether the next day's closing price will be higher or lower than the opening price, enabling informed decisions about buying or selling.

# Data Description
The dataset spans the period from 1997 to 2020, divided into:

#Training: 1997–2016
#Validation: 2016–2018
#Testing: 2018–2020

Each dataset contains the following columns:
#Date: Format YYYY-MM-DD
#Open: Opening stock price
#High: Highest stock price of the day
#Low: Lowest stock price of the day
#Close: Closing stock price
#Volume: Number of stocks traded
#Adjusted Close: Adjusted closing price accounting for stock splits and dividends

The target variable is binary:
1: Closing price > Opening price
0: Closing price ≤ Opening price

# Methodology
#Data Preprocessing:

Handled missing values, if any.
Scaled features for consistent input to the model.
Generated additional features, such as price changes or moving averages, to enhance predictions.
#Modeling:

Used machine learning classifiers to predict binary outcomes.
Evaluated performance using training, validation, and test datasets.

#Evaluation:

Metrics: Accuracy, precision, recall, and F1-score.
Visualizations for performance analysis.

