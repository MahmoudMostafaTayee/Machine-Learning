# 📈 G-Research Crypto Forecasting

A machine learning project focused on time-series forecasting and statistical analysis of cryptocurrency price trends using the G-Research Crypto Forecasting dataset.

## 🧠 Keywords
- Machine Learning  
- Time-Series Prediction  
- Statistical Analysis  
- Deep Learning (LSTM)  
- Cryptocurrency Forecasting  

## 📂 Project Overview

This project uses real-time financial market data from several cryptocurrencies to train machine learning models capable of predicting short-term returns. The dataset was provided as part of the **G-Research Crypto Forecasting** Kaggle competition.

## 📊 Dataset

The primary dataset contains over 24 million rows of minute-by-minute trading data for 14 major cryptocurrencies, including:

- Bitcoin  
- Ethereum  
- Litecoin  
- Monero  
- TRON  
- Cardano  
- Stellar  
- Dogecoin  
- And more...

Each record includes:
- `timestamp`
- `Asset_ID`
- `Open`, `High`, `Low`, `Close` prices
- `Volume`
- `VWAP` (Volume Weighted Average Price)
- `Target` (future return to be predicted)

Additional asset metadata (`asset_details.csv`) maps asset IDs to their names and weights.

## ⚙️ Technologies Used

- **Python**
- **NumPy**, **Pandas**
- **Matplotlib**, **Plotly**
- **scikit-learn**
- **TensorFlow / Keras**
- **LSTM Neural Networks**
- **MinMaxScaler**, **Log Returns**
- **Datetime and Timestamp Manipulation**

## 🚀 Model Workflow

1. **Data Loading**  
   Load historical price and metadata from CSV files.

2. **Data Preprocessing**  
   - Timestamp conversion to readable dates  
   - Feature scaling with `MinMaxScaler`  
   - Calculation of log returns

3. **Visualization & Exploration**  
   Plot trends for different cryptocurrencies using Matplotlib and Plotly.

4. **Modeling**  
   - Time-series windowing  
   - LSTM-based prediction model for price forecasting  
   - Evaluation using metrics like RMSE, MAE, R², etc.


## 📉 Sample Output

- Normalized and scaled crypto price series
- LSTM-predicted vs actual closing price plots
- Statistical evaluation metrics
