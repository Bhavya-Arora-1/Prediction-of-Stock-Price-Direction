#
Prediction of Stock Price Direction
---

## **Overview**  
This project predicts the next day's price direction of Amazon.com, Inc. (AMZN) stock using historical stock data. The goal is to determine whether the closing price will be higher or lower than the opening price, enabling better investment decisions.  

---

## **Features**  
- **Data Preprocessing**: Handles missing data, scales features, and generates additional variables such as percentage change and moving averages for better predictions.  
- **Model Implementation**: Applies machine learning classifiers for binary classification of price direction.  
- **Performance Metrics**: Evaluates model accuracy, precision, recall, and F1-score.  
- **Visualization**: Includes detailed plots for model performance and stock trend analysis.  

---

## **Dataset**  
The dataset contains historical stock prices for Amazon (AMZN) from 1997 to 2020, divided into three parts:  
- **Training Data**: 1997–2016  
- **Validation Data**: 2016–2018  
- **Testing Data**: 2018–2020  

Each dataset contains the following columns:  
1. **Date**: Format YYYY-MM-DD  
2. **Open**: Opening stock price  
3. **High**: Highest stock price of the day  
4. **Low**: Lowest stock price of the day  
5. **Close**: Closing stock price  
6. **Volume**: Number of stocks traded  
7. **Adjusted Close**: Adjusted closing price considering stock splits and dividends  

The target variable is binary:  
- **1**: Closing price > Opening price  
- **0**: Closing price ≤ Opening price  

---

## **Technologies Used**  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  

---

## **Prerequisites**  
- Python 3.8+  
- Jupyter Notebook  
- Required Libraries: Install using `pip install -r requirements.txt`  

---

## **Project Structure**  
```
project/
│-- AMZN_STOCK_Bhavya_Arora.ipynb  # Main Jupyter notebook
│-- data/
│    │-- AMZN_train.csv            # Training dataset
│    │-- AMZN_val.csv              # Validation dataset
│    │-- AMZN_test.csv             # Testing dataset
│-- requirements.txt               # List of dependencies
│-- README.md                      # Project overview
```  
