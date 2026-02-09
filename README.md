# ✈️ Airline Passenger Demand Forecasting using ARIMA

Accurate demand forecasting is critical for airline operations such as aircraft allocation,
workforce planning, and route scheduling. This project implements an **ARIMA (AutoRegressive
Integrated Moving Average)** model to forecast monthly airline passenger demand by effectively
handling **non-stationary time series data**.

---

## 📌 Project Overview

Historical airline passenger data shows a long-term upward trend, making the series
non-stationary. Forecasting without addressing this leads to unreliable predictions.
This project builds a complete ARIMA forecasting pipeline that:

- Identifies non-stationarity in time series data
- Applies differencing techniques
- Selects optimal ARIMA parameters (p, d, q)
- Evaluates model performance
- Generates future passenger demand forecasts

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries:**  
  - Pandas  
  - NumPy  
  - Statsmodels  
  - Matplotlib  


**Steps:**
1. Data Collection & Visualization  
2. Stationarity Check (ADF Test)  
3. Differencing to remove trend  
4. ACF & PACF analysis  
5. ARIMA model training  
6. Model evaluation  
7. Future demand forecasting  

---

## 📊 Dataset

- **Type:** Monthly airline passenger data  
- **Features:**
  - Month
  - Number of Passengers  
- **Characteristics:**
  - Upward trend
  - Non-stationary behavior

---

## 📈 Model Evaluation

The ARIMA model performance is evaluated using:

- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**

📌 *<img width="831" height="451" alt="image" src="https://github.com/user-attachments/assets/97ba481a-d887-4ccd-b554-49f6a930a7d9" />


---

## 🔮 Results

- Successfully transformed non-stationary data into stationary form
- ARIMA model produced reliable and accurate forecasts
- Predictions closely followed actual passenger trends
- Demonstrated real-world applicability in airline demand planning

📌 <img width="831" height="451" alt="image" src="https://github.com/user-attachments/assets/002eee29-bf22-4fb3-a744-cd280648babd" />


---

## 🚀 Applications

- Aircraft capacity planning
- Workforce scheduling
- Route demand analysis
- Revenue forecasting

---

## 🔧 Future Enhancements

- Implement **SARIMA** to capture seasonality
- Compare ARIMA with **LSTM** and **Prophet**
- Use real-time airline booking data
- Deploy model using a web dashboard

---

## 📚 References

- Box, G. E. P., Jenkins, G. M., Reinsel, G. C. – *Time Series Analysis*
- Statsmodels Documentation
- Airline Passenger Dataset

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.
Feel free to fork the repository and submit a pull request.

---

⭐ If you found this project useful, consider giving it a star!


