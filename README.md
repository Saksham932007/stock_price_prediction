# 📈 Stock Price Prediction using LSTM (Colab Ready)

This project implements a stock price prediction pipeline using **LSTM (Long Short-Term Memory) neural networks** in TensorFlow/Keras.  
It is designed to run seamlessly in **Google Colab**, making it easy to experiment, train, and evaluate models on financial time-series data.

---

## 🚀 Features
- Fetch historical stock data using [yfinance](https://pypi.org/project/yfinance/)
- Preprocess data with **MinMaxScaler**
- Create time-series sequences for supervised learning
- Build and train an **LSTM model** with:
  - Early Stopping  
  - ReduceLROnPlateau  
  - Model Checkpointing
- Evaluate model performance with:
  - **MAE** (Mean Absolute Error)  
  - **RMSE** (Root Mean Squared Error)  
  - **MAPE** (Mean Absolute Percentage Error)
- Plot actual vs predicted prices for **train** and **test** sets
- Perform simple **multi-step forecasting** for upcoming days

---

## 🛠 Tech Stack
- **Python 3.10+**
- [TensorFlow](https://www.tensorflow.org/)
- [scikit-learn](https://scikit-learn.org/)
- [yfinance](https://pypi.org/project/yfinance/)
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)

---

## 📂 Project Structure
