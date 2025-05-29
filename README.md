<<<<<<< HEAD
# 📈 Ethereum (ETH/USDT) Price Forecasting using ARIMA

This project applies **Time Series Analysis** and the **ARIMA model** to forecast Ethereum (ETH/USDT) prices using historical data. The objective is to uncover patterns, test for stationarity, and generate reliable forecasts for future price trends in the cryptocurrency market.

---

## 🎯 Objective

- Analyze historical Ethereum price data.
- Identify trends, volatility, and seasonality.
- Apply ARIMA modeling for future price prediction.
- Visualize forecast results and evaluate model performance.

---

## 🗂 Dataset

- **Source:** Kaggle (Cryptocurrency Historical Price Data)
- **Key Columns:**
  - `Date`, `Open`, `High`, `Low`, `Close`, `Volume`, `Market Cap`
- **Preprocessing Includes:**
  - Setting `Date` as index.
  - Handling duplicates and missing values.
  - Selecting relevant features.
  - Checking and converting data types.

---

## 🔍 Exploratory Data Analysis (EDA)

- Line plot of `Close` price.
- 30-day Moving Average analysis.
- Volume vs Close price trend.
- Summary statistics (`.describe()`)
- Dataset shape and structure checks.

---

## 🧪 Stationarity Testing

- **Augmented Dickey-Fuller (ADF) Test**
  - Tested raw and differenced data.
  - Differencing applied to achieve stationarity.

---

## 🔄 ACF & PACF Analysis

- **ACF (AutoCorrelation Function)**: Helps identify the MA(q) term.
- **PACF (Partial AutoCorrelation Function)**: Helps determine the AR(p) term.
- Optimal ARIMA order selected as **(2, 1, 1)**.

---

## ⚙️ ARIMA Model Development

- Built ARIMA model using Statsmodels.
- Evaluated with metrics:
  - RMSE (Root Mean Squared Error)
  - MAPE (Mean Absolute Percentage Error)
  - R² Score

---

## 📉 Residual Analysis

- Residuals plotted to verify randomness.
- Histogram checked for normal distribution of errors.

---

## 📊 Forecasting

- Forecasted next **30 days** of prices.
- Plotted with **confidence intervals**.

---

## 🧰 Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels
- Scikit-learn

---

## 📁 Project Structure




---

## 📷 Visuals

- ✅ Ethereum Close Price with Moving Average  
- ✅ ADF Test and Differencing  
- ✅ ACF/PACF Plots  
- ✅ Actual vs Forecasted Prices  
- ✅ Residual and Forecast Plots

---

## 📚 References

- [ARIMA Forecasting Guide – MachineLearningPlus](https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/)
- Kaggle Datasets
- Statsmodels Documentation

---

## 👨‍💻 Author

**Mirza Yasir Abdullah Baig**  
Intern, Arch Technology 
📧 Email: yasirabdullah4549@gmail.com
🌐 GitHub: https://github.com/mirzayasirabdullahbaig07/

