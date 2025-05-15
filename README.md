# Predicting-the-Stock-Prices-using-the-GRU-Neural-networks
This project uses a Gated Recurrent Unit (GRU) neural network in PyTorch to predict stock prices, leveraging historical data from yfinance. It supports historical price prediction, recursive future forecasting (e.g., for June 2025), 



## Features
- **Historical Prediction**: Trains a GRU model to predict stock prices on historical data (e.g., AAPL from 2015 to 2025).
- **Future Forecasting**: Recursively predicts future prices (e.g., May 30, 2025) using the last 60 days of data.
- **Data Processing**: Fetches real-time stock data with yfinance, normalizes with MinMaxScaler, and creates sequences for time-series modeling.
- **Evaluation**: Computes MSE, RMSE, and MAE to assess model performance, with visualizations of actual vs. predicted prices.
- **Efficient Training**: Uses DataLoader with batch size of 32 to handle large datasets (~2553 sequences).

## Technologies
- **Python 3.8+**
- **PyTorch**: For building and training the GRU model.
- **yfinance**: For fetching stock price data.
- **NumPy, Pandas**: For data manipulation.
- **Scikit-learn**: For MinMaxScaler normalization.
- **Matplotlib**: For plotting predictions.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Raghava2004-cpu/Predicting-the-Stock-Prices-using-the-GRU-Neura-networks.git
   cd Predicting-the-Stock-Prices-using-the-GRU-Neura-networks-gru

   '''blash
    pip install -r requirements.txt


![Screenshot 2025-05-15 125902](https://github.com/user-attachments/assets/8cb96520-d45a-47b3-ac72-98faa652b7fb)
![Screenshot 2025-05-15 125946](https://github.com/user-attachments/assets/e5f4c491-ea96-42de-ae3d-99039b43f5cd)
![Screenshot 2025-05-15 125956](https://github.com/user-attachments/assets/7b416e92-2e63-4130-9ddd-d06fc00ec510)


