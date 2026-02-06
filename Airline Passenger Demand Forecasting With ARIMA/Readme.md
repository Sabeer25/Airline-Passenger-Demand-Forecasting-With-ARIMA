
# ✈️ Airline Passenger Demand Forecasting with ARIMA

## 📌 Project Overview
This project focuses on **forecasting monthly airline passenger demand** using the **ARIMA (AutoRegressive Integrated Moving Average)** time series model.  
Accurate demand forecasting helps airlines optimize **aircraft allocation, workforce planning, and route scheduling**.

The project demonstrates how to handle **non-stationary time series data** by applying statistical techniques such as **differencing, autocorrelation analysis, and stationarity testing** before building a forecasting model.

---

## 📊 Problem Statement
Historical airline passenger data exhibits a **long-term growth trend and seasonality**, making it **non-stationary**.  
Forecasting without addressing this non-stationarity leads to unreliable predictions.

This project applies **ARIMA modeling** to:
- Identify non-stationarity
- Transform the data into a stationary series
- Build a robust forecasting model
- Predict future passenger demand

---

## 📁 Dataset
The project uses monthly airline passenger data with the following structure:

| Column       | Description                          |
|--------------|--------------------------------------|
| Month        | Date of passenger record (monthly)   |
| Passengers   | Number of airline passengers         |

📌 The dataset spans multiple years and shows clear **trend and seasonal patterns**.

---

## 🔍 Techniques Used
- Time Series Visualization  
- Trend Analysis  
- Differencing for Stationarity  
- Autocorrelation Function (ACF)  
- Partial Autocorrelation Function (PACF)  
- Augmented Dickey-Fuller (ADF) Test  
- ARIMA Model Building  
- Forecast Accuracy Evaluation (MAE, RMSE)  

---

## 🛠️ Tools & Libraries
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Statsmodels**
- **Scikit-learn**

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/airline-passenger-demand-forecasting-arima.git
cd airline-passenger-demand-forecasting-arima

###2️⃣ Install Dependencies
```bash
pip install -r requirements.txt

###3️⃣ Run the Project
```bash
python src/main.py
