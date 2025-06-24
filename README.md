# Predict Future Stock Prices (Short-Term)

This project is part of my AI/ML internship tasks. It focuses on building a regression model to predict the next day's closing stock price using historical data.

---

## 🎯 Task Objective
Use historical stock data to predict the **next day's closing price** using features such as Open, High, Low, and Volume.

---

## 📁 Dataset Used
- **Source**: Yahoo Finance
- **Accessed via**: `yfinance` Python library
- **Stock Example**: Apple (AAPL) / Tesla (TSLA)
- **Features Used**: `Open`, `High`, `Low`, `Volume`
- **Target Variable**: `Close`

---

## 🤖 Models Applied
- **Linear Regression**
- **Random Forest Regressor**

---

## 📊 Key Results and Findings
- **Random Forest** performed better than Linear Regression on most runs due to its ability to model non-linear patterns.
- **Evaluation Metrics**:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
- **Visualization**: Actual vs Predicted closing prices were plotted to assess model performance visually.

---

## 🛠️ Skills Demonstrated
- Time series data handling
- API-based data fetching (`yfinance`)
- Regression modeling
- Performance evaluation (MAE, RMSE)
- Plotting and result interpretation

---

> 📌 This task builds practical skills in working with real-time financial data and applying ML models for prediction.

