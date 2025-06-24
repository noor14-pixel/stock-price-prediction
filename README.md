# Predict Future Stock Prices (Short-Term)

This project is part of my AI/ML internship tasks. It focuses on building a regression model to predict the next day's closing stock price using historical data.

---

## 🎯 Task Objective
Use historical stock data to predict the **next day's closing price** using features such as Open, High, Low, and Volume.

---

## 📁 Dataset Used
- **Source**: Yahoo Finance  
- **Accessed via**: `yfinance` Python library  
- **Stock Example**: Apple (AAPL)  
- **Features Used**: `Open`, `High`, `Low`, `Volume`  
- **Target Variable**: `Close`

---

## 🤖 Model Applied
- **Linear Regression**

---

## 📊 Key Results and Findings
- **R² Score**: `0.9291`  
- **RMSE**: `3.77`

The model performed well, achieving a strong R² value and low RMSE, indicating that **Linear Regression** was effective in capturing the trend of stock prices in this short-term prediction setting.

- **Visualization**: A plot of actual vs predicted closing prices helped visually confirm model performance.

---

## 🛠️ Skills Demonstrated
- Time series data handling  
- API-based data fetching with `yfinance`  
- Regression modeling with `sklearn`  
- Model evaluation using R² and RMSE  
- Data visualization with `matplotlib`

---

> 📌 This task enhanced my understanding of financial data and how simple regression techniques can be used for predictive modeling.
