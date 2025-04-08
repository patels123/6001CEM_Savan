# 📈 Stock Price Prediction Using Machine Learning  
**Case Study: HSBC PLC**  

This project aims to build and evaluate machine learning models to predict the stock prices of HSBC PLC using historical data from 2010 to 2025. It applies various supervised learning algorithms and time series techniques to identify the most accurate and robust model for forecasting.

---

## 🧠 Project Overview

Stock markets are inherently volatile, and accurate predictions can greatly benefit investors and institutions. This project explores how machine learning can be leveraged to forecast stock prices using historical OHLC (Open, High, Low, Close), volume, and market capitalization data.

---

## 🎯 Objectives

- Understand the benefits and challenges of stock price prediction.
- Collect and preprocess historical stock price data.
- Apply multiple machine learning models.
- Evaluate and compare model performance.
- Recommend the best-performing model for stock prediction.

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** – Data handling
- **NumPy** – Numerical operations
- **Matplotlib / Seaborn** – Data visualization
- **Scikit-learn** – ML models (Linear Regression, SVM, Random Forest)
- **XGBoost** – Gradient boosting model
- **Statsmodels** – ARIMA for time series forecasting

---

## 🧪 Models Applied

| Model                | RMSE   | MAE   | R² Score |
|---------------------|--------|-------|----------|
| ARIMA               | 1.21   | 0.96  | -1.02     |
| Linear Regression   | 0.21   | 0.17  | 0.94     |
| Support Vector Machine | 0.30 | 0.22  | 0.87     |
| Random Forest       | 0.31   | 0.24  | 0.86     |
| XGBoost             | 0.33   | 0.26  | 0.85     |

✅ **Best Performing Model:** Linear Regression

---

## 🔍 Dataset

- Source: https://fame-r1.bvdinfo.com/version-20250318-2-0/fame/1/Companies/report/Index?backLabel=Back%20to%20Contents&format=_standard&BookSection=PROFILE&seq=0&sl=1744155987460
- Features used: `Open`, `High`, `Low`, `Close`, `Volume`, `Market Cap`
- Time Range: May 2010 – April 2025  
- Total Records: ~3720

---

## 🔧 Features Engineered

- Daily Return  
- Volatility (High - Low)  
- Moving Averages (30-day & 90-day)  
- Volume Change %  

---

## 📊 Exploratory Data Analysis (EDA)

- Trend Analysis (2010–2025)
- Volume and Price Correlation
- Moving Average Volatility
- Heatmaps for feature correlation
- Outlier detection and removal

---

## 📈 Model Evaluation Metrics

- Root Mean Square Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score (Coefficient of Determination)

---

## 🔐 Ethical Considerations

- Data is used strictly for educational and research purposes.
- No proprietary or sensitive financial data was used.
- Ethical data handling and storage practices were followed.

---

## 📌 Recommendations

- Perform hyperparameter tuning for models like XGBoost and SVM.
- Include technical indicators like RSI, MACD in future versions.
- Extend to other stocks or indices (e.g., Nasdaq, Nifty50).
- Integrate sentiment analysis from news and social media.

---

## 📚 References

This project references 17 academic papers and articles. See full list in the [`References`](./References.md) section of the dissertation.

---

## 🤝 Acknowledgements

- Supervisor: **Dr. Kamal Bentahar**
- Coventry University – Final Year Individual Project (6001CEM)

---

## 🧾 License

This project is open for academic use and personal experimentation. Not intended for real-time financial trading or investment decisions.
