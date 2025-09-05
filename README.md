# Automated Crypto Trading Bot (Coinbase + ML)

This project combines **Machine Learning (LSTM + XGBoost)** with **real-time trading logic**  
to create an **automated trading bot** integrated with the Coinbase API.  

It experiments with predictive modeling, scalping strategies, and risk management on cryptocurrencies like **BTC, DOGE, and SHIB**.

---

## 📌 Project Overview
- **Data Sources**:
  - `btc_prices.csv` (historical data)
  - Coinbase API (real-time prices)
- **ML Models**:
  - LSTM (TensorFlow/Keras)
  - XGBoost for price movement prediction
- **Trading Logic**:
  - Real-time inference from trained model
  - Scalping strategy (RSI + ATR indicators)
  - Stop-loss & take-profit rules
  - Trade logging (`trade_logs.csv`, `stats_logs.csv`)

---

## 📂 Repository Structure
ml-crypto-bot/
├── Doge&Shib.ipynb # DOGE & SHIB scalping strategy
├── model_training_checkpoints.ipynb # ML model training
├── real_time_trading.ipynb # Live trading logic
├── checkpoints/ # Saved models (e.g., shib_model.keras)
├── data/ # Historical CSVs
├── logs/ # Trade & stats logs
└── README.md


---

## 📊 Example Features
- Moving averages, RSI, volatility, ATR.
- Adaptive stop-loss & profit targets.
- Multi-threaded execution for multiple assets.

---

## 🚀 Why This Project
- Demonstrates **end-to-end algo-trading system design**.
- Combines **ML predictions** with **classical technical analysis**.
- Showcases **real-time engineering skills** (APIs, logging, automation).

---

## 🧠 Skills Demonstrated
- Time-series modeling (LSTM, XGBoost).
- Hyperparameter tuning with Optuna.
- Feature engineering (returns, volatility).
- API integration (Coinbase REST API).
- Trading strategy design & risk management.
