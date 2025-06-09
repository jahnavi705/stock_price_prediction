# stock_price_prediction

# Overview :
   This project demonstrates how to predict future stock price trends using a Long Short-Term Memory (LSTM) neural network—a type of recurrent neural network well-suited for time series forecasting. The model is trained on historical stock data, and incorporates technical indicators such as the Moving Average and RSI (Relative Strength Index) to enhance predictive power.

# Objective :
   To build an LSTM-based model that predicts future closing prices of a stock by learning patterns from its historical data. The project also includes data visualization and optional deployment using Streamlit for interactive forecasting.

# Tools & Libraries Used :
  - Python
  - Keras
  - Pandas
  - Matplotlib
  - yfinance
  - Scikit-learn

# Workflow :
 1. Data Collection
   - Historical stock price data is fetched using the yfinance API.
   - Focus is primarily on the closing prices, along with volume and date.
     
 2. Data Preprocessing
   - Data is cleaned and normalized using MinMaxScaler to scale values between 0 and 1.
   - Create sequences of time steps (e.g., 60 days) to predict the next day's price.
   - Train-test split to evaluate performance.
     
 3. Feature Engineering
   - Add technical indicators:
     - Moving Average (MA)
     - Relative Strength Index (RSI)
   - These indicators provide additional insight into market trends and price momentum.
     
 4. Model Building
   - An LSTM model is created using Keras.
   - The model is trained on the processed time series data.
   - Validation is performed using a separate dataset.
     
 5. Prediction & Visualization
  - The trained model is used to make predictions on unseen data.
  - Visualize actual vs. predicted prices using Matplotlib.
  - Evaluate model performance using metrics like MSE and RMSE.

# Output :

 - Graphs comparing actual and predicted stock prices
 - Visualization of RSI and moving averages

![a](https://github.com/user-attachments/assets/0a94dd4c-0c82-41c7-b204-9ca1847baa89)

![b](https://github.com/user-attachments/assets/1bdf1058-d17b-4b3b-b879-8d618280ebb9)

![c](https://github.com/user-attachments/assets/b4fd4ea0-a07d-4c23-9eb1-eb9f8da424cd)

