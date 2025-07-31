# Stock-Price-Trend-Prediction-Using-XGBoost
This project focuses on predicting the direction of S&amp;P 500 stock price movements (up or down) using the XGBoost Classifier, a powerful gradient boosting algorithm.

Rather than forecasting exact price values, the model predicts whether the next day's closing price will go **up (1)** or **down (0)** relative to the current day — a **binary classification task** focused on price trend detection.

---

## 🚀 Project Highlights

- 🧠 Built and validated XGBoost models for directional price prediction.
- 📊 Engineered time series features including **moving averages**, **RSI**, **MACD**, **lagged returns**, and **exponential smoothing**.
- 🔁 Used **walk-forward backtesting** to simulate real-world prediction scenarios and avoid data leakage.
- 🧪 Applied **GridSearchCV** with `TimeSeriesSplit` for robust hyperparameter tuning.
- 🧮 Analyzed **directional mismatches** pre- and post-smoothing to quantify signal distortion.

---

## 🛠️ Tools & Technologies

- **Python**  
- **XGBoost**  
- **Scikit-learn**  
- **Pandas, NumPy, Matplotlib**  
- **Time Series Analysis** techniques 
