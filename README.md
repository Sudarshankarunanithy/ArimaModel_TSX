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

## 📁 Project Structure

tsx-forecasting-ml/ │ 
├── notebooks/ # Step-by-step analysis notebooks │ 
  ├── 1_eda_tsx_analysis.ipynb │ 
  ├── 2_arima_modeling.ipynb │ 
  ├── 3_feature_engineering.ipynb │ 
  ├── 4_ml_models_forecasting.ipynb │ 
  ├── 5_model_comparison.ipynb 
  │ └── 6_lstm_forecasting.ipynb │ 
├── models/  
├── plots/ # Exported visualizations 
│ └── arima_tsx_forecast.png │ 
├── requirements.txt # Project dependencies
├── README.md # Project overview └── .gitignore # Ignore files for version control
