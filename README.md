# Stock Price Prediction using Linear Regression and Random Forest

This project aims to predict stock closing prices using two supervised machine learning algorithms: **Linear Regression** and **Random Forest Regressor**. The model is trained on historical stock market data and evaluated using common regression metrics.

---

## Features

- Fetch and preprocess historical stock data (e.g., from Yahoo Finance)
- Train and compare Linear Regression and Random Forest models
- Visualize actual vs predicted prices
- Evaluate model performance using MAE, MSE, and R² score

## Project Structure

├── data/
│   └── stock_data.csv            # Historical stock price data
├── models/
│   └── linear_regression.pkl     # Saved Linear Regression model
│   └── random_forest.pkl         # Saved Random Forest model
├── notebooks/
│   └── stock_prediction.ipynb    # Jupyter notebook with code
├── README.md
└── requirements.txt


## Algorithms Used

- **Linear Regression**  
  A basic regression model to predict continuous values based on historical trends.

- **Random Forest Regressor**  
  An ensemble model that uses multiple decision trees for improved prediction accuracy and robustness.


## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- yfinance (optional, for real-time data)

Install dependencies with:

```bash
pip install -r requirements.txt
```


## How to Run

1. Clone the repository
2. Place your stock data CSV file inside the `data/` folder
3. Run the notebook or script:
   ```bash
   jupyter notebook notebooks/stock_prediction.ipynb
   ```


## Example Output

- Actual vs Predicted stock prices plot
- Performance metrics table (MAE, MSE, R²)


## Future Improvements

- Add more features like technical indicators (SMA, RSI, etc.)
- Try other models like XGBoost, LSTM (deep learning)
- Deploy the model as a web app using Streamlit or Flask
