# ⛽ Petrol Demand Forecasting using Time Series

## 📘 Project Overview
This project forecasts **petrol demand** using **time series models** like SARIMA/SARIMAX and LSTM.  
It helps to analyze demand trends, optimize inventory, and reduce stockouts.

The project is divided into **three stages**:
1. **Stage 1 – Data Cleaning & Exploration**  
   Cleans raw petrol demand data, handles missing values, and prepares it for analysis.  
2. **Stage 2 – Feature Engineering & Visualization**  
   Creates time-based, lag, and rolling features. Performs ADF test, seasonal decomposition, and ACF/PACF analysis.  
3. **Stage 3 – Forecasting & KPI Analysis**  
   Builds SARIMA and LSTM models, forecasts demand, and compares models using KPIs (RMSE, Stockout %, Overstock %, Revenue Growth).

## 🧠 Models Used

| Model | Description |
|--------|--------------|
| **SARIMA/SARIMAX** | Traditional time series model capturing trend and seasonality. |
| **LSTM (Long Short-Term Memory)** | Deep learning model capable of learning long-term nonlinear dependencies. |

---

## 📈 Results & Outputs

| Output File | Description |
|--------------|--------------|
| `model_comparison_plot.png` | Comparison of Actual vs Predicted values using SARIMA & LSTM |
| `forecast_next7days.png` | Forecast for next 7 days showing future demand trends |

---

## 📊 Key Insights

- **SARIMA** gives better short-term, interpretable results.  
- **LSTM** performs well on nonlinear demand with spikes.  
- Combining both improves accuracy and business decision-making.  
- Forecasting helps reduce **stockout and overstock risks** while improving **revenue growth**.

---

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Statsmodels, TensorFlow/Keras)
- Google Colab
- Scikit-learn

