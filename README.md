# ⚡ National Electricity Demand Forecasting——Case study for Panama

📊 **A Comparative Study of Traditional and Deep Learning Models**

---

## 📌 Project Overview

This project aims to forecast national electricity demand using three distinct modeling approaches: **Winters' Exponential Smoothing**, **ARIMA**, and **LSTM Deep Learning**. The goal is to compare their effectiveness in capturing seasonal trends, linear dependencies, and complex temporal patterns in electricity consumption data. The study focuses on Panama's electricity load data, incorporating meteorological variables and holiday indicators to enhance prediction accuracy.

---

## 🗂️ Dataset

- **Source**: [Electricity Load Forecasting](https://www.kaggle.com/datasets/saurabhshahane/electricity-load-forecasting/data) (Kaggle)  
- **Time Span**: January 2015 to June 2020  
- **Features**:
  - Hourly national electricity demand (`nat_demand`)
  - Meteorological data (temperature, humidity, precipitation, wind speed) from three cities
  - Workday/holiday indicators

---

## 🛠️ Methodology

### 📈 Traditional Models
1. **Winters' Exponential Smoothing**  
   - Captures fixed seasonal trends and linear patterns.
   - Optimized for single seasonality (e.g., annual cycles).

2. **ARIMA (Autoregressive Integrated Moving Average)**  
   - Models linear dependencies and autocorrelation.
   - Handles non-stationary data through differencing.

### 🤖 Deep Learning Model
3. **LSTM (Long Short-Term Memory)**  
   - Processes complex temporal dependencies and multiple seasonality.
   - Incorporates exogenous variables (weather, holidays) for robust predictions.
   - Uses sequence learning with lagged features and rolling statistics.

---

## 🚀 Key Insights

- **Winters' Method**: Effective for simple seasonality but struggles with multiple/irregular patterns.
- **ARIMA**: Strong linear fitting but limited generalization on unseen data.
- **LSTM**: Superior performance in handling nonlinear trends, sudden fluctuations, and multivariate inputs.

---

## 🔮 Future Enhancements

- Integrate **additional external variables** (e.g., economic indicators, extreme weather events).
- Explore advanced architectures like **Transformers** or hybrid models.
- Implement **continual learning** to adapt to evolving data patterns.
- Improve model **interpretability** for real-world deployment.

---

## 👥 Contributors

- Ruitong Liu | Yuanchang Cai | Zhengxi Xu  
- Ziyi Zhou | Zixiang Zheng | Jingyang Zhang  
- *Department of Business, Macau University of Science and Technology*

---
