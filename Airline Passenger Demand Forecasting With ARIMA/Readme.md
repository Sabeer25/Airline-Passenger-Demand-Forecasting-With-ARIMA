{\rtf1\ansi\ansicpg1252\cocoartf2867
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fnil\fcharset0 .SFNS-Semibold;}
{\colortbl;\red255\green255\blue255;\red14\green14\blue14;}
{\*\expandedcolortbl;;\cssrgb\c6700\c6700\c6700;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # \uc0\u9992 \u65039  Airline Passenger Demand Forecasting with ARIMA\
\
## \uc0\u55357 \u56524  Project Overview\
This project focuses on **forecasting monthly airline passenger demand** using the **ARIMA (AutoRegressive Integrated Moving Average)** time series model.  \
Accurate demand forecasting helps airlines optimize **aircraft allocation, workforce planning, and route scheduling**.\
\
The project demonstrates how to handle **non-stationary time series data** by applying statistical techniques such as **differencing, autocorrelation analysis, and stationarity testing** before building a forecasting model.\
\
---\
\
## \uc0\u55357 \u56522  Problem Statement\
Historical airline passenger data exhibits a **long-term growth trend and seasonality**, making it **non-stationary**.  \
Forecasting without addressing this non-stationarity leads to unreliable predictions.\
\
This project applies **ARIMA modeling** to:\
- Identify non-stationarity\
- Transform the data into a stationary series\
- Build a robust forecasting model\
- Predict future passenger demand\
\
---\
\
## \uc0\u55357 \u56513  Dataset\
The project uses monthly airline passenger data with the following structure:\
\
| Column       | Description                          |\
|--------------|--------------------------------------|\
| Month        | Date of passenger record (monthly)   |\
| Passengers   | Number of airline passengers         |\
\
\uc0\u55357 \u56524  The dataset spans multiple years and shows clear **trend and seasonal patterns**.\
\
---\
\
## \uc0\u55357 \u56589  Techniques Used\
- Time Series Visualization  \
- Trend Analysis  \
- Differencing for Stationarity  \
- Autocorrelation Function (ACF)  \
- Partial Autocorrelation Function (PACF)  \
- Augmented Dickey-Fuller (ADF) Test  \
- ARIMA Model Building  \
- Forecast Accuracy Evaluation (MAE, RMSE)  \
\
---\
\
## \uc0\u55357 \u57056 \u65039  Tools & Libraries\
- **Python**\
- **Pandas**\
- **NumPy**\
- **Matplotlib**\
- **Statsmodels**\
- **Scikit-learn**\
\
---\
\
## \uc0\u55357 \u56960  How to Run the Project\
\
### 1\uc0\u65039 \u8419  Clone the Repository\
```bash\
git clone https://github.com/your-username/airline-passenger-demand-forecasting-arima.git\
cd airline-passenger-demand-forecasting-arima\
\
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\sl324\slmult1\pardirnatural\partightenfactor0

\f1\b \cf2 ###2\uc0\u65039 \u8419  Install Dependencies\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\b0 \cf0 ```bash
\f1\b\fs30 \cf2 \
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\sl324\slmult1\pardirnatural\partightenfactor0

\fs24 \cf2 pip install -r requirements.txt\

\fs30 \

\fs24 ###3\uc0\u65039 \u8419  Run the Project\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\b0 \cf0 ```bash
\f1\b\fs30 \cf2 \
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\sl324\slmult1\pardirnatural\partightenfactor0

\fs24 \cf2 python src/main.py}