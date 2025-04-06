# 📈 TSX Composite Index Forecasting using ARIMA and Machine Learning

This project forecasts the daily closing prices of the **S&P/TSX Composite Index (`^GSPTSE`)** using a combination of classical time series models and machine learning approaches. It aims to compare performance between models like **ARIMA**, **Linear Regression**, **Random Forest**, **XGBoost**, and **LSTM**.

---

## 🧠 Project Objective

- To analyze historical TSX index trends
- To predict future values for the next 7 days
- To compare classical time series models with machine learning and deep learning models
- To build a reusable pipeline for financial time series forecasting

---

## 📊 Data Source

- **Yahoo Finance** via `yfinance` library
- Index: **S&P/TSX Composite Index (`^GSPTSE`)**
- Period: From 2018 to 2025 (customizable)

---

## 🛠️ Technologies Used

| Category           | Tools/Libraries                           |
|--------------------|--------------------------------------------|
| Language           | Python                                     |
| Data Collection    | `yfinance`                                 |
| Analysis & Viz     | `pandas`, `matplotlib`, `seaborn`          |
| Time Series Model  | `statsmodels`, `pmdarima`                  |
| Machine Learning   | `scikit-learn`, `xgboost`                  |
| Deep Learning      | `tensorflow` (LSTM)                        |
| Environment Mgmt   | `venv`, `requirements.txt`                 |

---


---

## 🔬 Methodology

### 1. **EDA (Exploratory Data Analysis)**
- Visualize historical trends
- Calculate returns and moving averages
- Identify patterns and outliers

### 2. **ARIMA Modeling**
- Test stationarity using ADF test
- Use `auto_arima` or manual tuning
- Forecast next 7 days

### 3. **Feature Engineering**
- Create lag features (t-1 to t-7)
- Rolling mean and standard deviation
- Train/test split for ML

### 4. **Machine Learning Models**
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

### 5. **Deep Learning (Optional)**
- LSTM using TensorFlow/Keras
- Reshape data and train sequence model

---

## 📈 Evaluation Metrics

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- MAPE (Mean Absolute Percentage Error)
- Visual comparison of predicted vs actual

---

## 📌 Sample Visualizations

![TSX Close Forecast](plots/arima_tsx_forecast.png)

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tsx-forecasting-ml.git
   cd tsx-forecasting-ml

├── plots/ # Exported visualizations 
│ └── arima_tsx_forecast.png │ 
├── requirements.txt # Project dependencies
├── README.md # Project overview └── .gitignore # Ignore files for version control
