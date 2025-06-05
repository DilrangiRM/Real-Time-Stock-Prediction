# 📈 AAPL Stock Price Movement Prediction using MLP, RNN, and LSTM

This project uses machine learning and deep learning techniques to predict the next-day stock price movement (up/down) of Apple Inc. (AAPL). It involves downloading stock data, preprocessing, feature engineering, and building three models—MLP (Multilayer Perceptron), Simple RNN, and LSTM. The models are evaluated using various performance metrics and ROC curves.

---

## 📌 Key Features

- ✅ Automatically fetches 1-year of daily AAPL stock data using `yfinance`
- ✅ Removes outliers using Z-Score technique
- ✅ Scales features using Min-Max Scaling
- ✅ Creates a binary classification target: Will the price go up the next day?
- ✅ Trains and compares the following models:
  - MLP (Multilayer Perceptron)
  - Simple RNN
  - LSTM
- ✅ Evaluates models using:
  - Accuracy, Precision, Recall, F1 Score, Confusion Matrix
  - ROC Curve with AUC Score

---

## 📊 Example Output

Each model prints its metrics and plots a ROC curve.  
Example:

