<div align="center">
  <h1>📈 Air Passengers: Time Series Analysis & Forecasting</h1>
  <p><i>Unlocking patterns in aviation traffic using statistical decomposition and predictive modeling.</i></p>
  
  ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
  ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
  ![Statsmodels](https://img.shields.io/badge/statsmodels-blue?style=for-the-badge)
</div>

---

### 🌟 Project Overview
This repository contains an end-to-end **Time Series Analysis** project focused on predicting airline passenger traffic. The analysis explores statistical patterns, data stability, and predictive modeling using the classic Air Passengers dataset.

### 🚀 Key Highlights
The project moves beyond simple plotting to provide a deep dive into the mechanics of time-based data:

* **Exploratory Data Analysis (EDA):** Uncovering long-term trends and repetitive seasonal cycles in aviation traffic.
* **Stationarity & Transformation:** Using the **Augmented Dickey-Fuller (ADF) Test** to detect non-stationarity and applying log-scaling and differencing to "stabilize" the data.
* **Decomposition:** Breaking the series into its core components: **Trend, Seasonality, and Residuals**.
* **Correlation Modeling:** Analyzing **ACF** and **PACF** plots to determine the mathematical relationship between past and future observations.

---

### 📊 Insights & Results
* **Trend:** Observed a consistent upward trajectory in passenger numbers year-over-year.
* **Seasonality:** Identified a clear seasonal pattern, with peak travel occurring during specific recurring months.
* **Stability:** Successfully transformed the non-stationary series into a stationary one for reliable forecasting.

---

### 📂 Getting Started

#### ⚙️ Installation
```bash
pip install pandas matplotlib statsmodels
