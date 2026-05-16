# Financial Market Forecasting Using Time Series Analysis

## 📌 Introduction
The financial market is a highly dynamic and unpredictable sector that involves numerous investors, buyers, and sellers. Predicting stock prices has been a significant challenge since the advent of machine learning. However, only a few techniques have proven to be effective in forecasting market trends as prices fluctuate over time.

Since **time** plays a crucial role in financial market movements, **Time Series (TS) analysis** can be leveraged to predict short-term price trends. This project explores the **ARIMA** model and its variants to forecast prices efficiently.

---

## 🛠 Methodology
### 1️⃣ Checking Data Stationarity
The first step in **Time Series Analysis** is to verify whether historical financial data is stationary. This is achieved using:
- **Plotting Rolling Statistics** to visualize trends
- **Dickey-Fuller Test** for statistical validation

### 2️⃣ Eliminating Trend and Seasonality
To make the data stationary, **trend** and **seasonality** are removed from the series.

### 3️⃣ Applying Time Series Models
Once the data is stationary, we apply the **ARIMA (Autoregressive Integrated Moving Average) model**, which is widely used in financial forecasting due to its efficiency in short-term predictions. For comparison, we also apply:
- **Autoregressive (AR)**
- **Moving Average (MA)**
- **Autoregressive Moving Average (ARMA)**

### 4️⃣ Forecasting and Reversing Transformations
The forecasted values are **converted back to the original scale** by reapplying trend and seasonality constraints.

---

## 🔍 Why ARIMA?
ARIMA has been extensively used in financial and economic sectors due to:
✔️ **High accuracy** in short-term predictions
✔️ **Effectiveness in handling non-stationary data**
✔️ **Strong theoretical foundation** in statistical modeling

---

## 📂 Project Structure
```
📁 Financial-Market-Forecasting
│── 📄 README.md        # Project Documentation
│── 📂 data             # Historical market data
│── 📂 notebooks        # Jupyter notebooks for analysis
│── 📂 models           # Trained ARIMA models
│── 📜 requirements.txt # Dependencies for the project
│── 📜 main.py          # Script for running the prediction
```

---

## 🚀 How to Run the Project
### 1️⃣ Install Dependencies
Ensure you have Python installed, then install required libraries:
```bash
pip install -r requirements.txt
```

### 2️⃣ Run the Prediction Model
Execute the main script to train the model and generate predictions:
```bash
python main.py
```

---

## 📊 Example Results
| Date       | Actual Price | Predicted Price |
|------------|-------------|----------------|
| 2024-02-01 | $150.25     | $149.80        |
| 2024-02-02 | $151.00     | $150.90        |
| 2024-02-03 | $152.75     | $152.10        |

---

## 📈 Future Improvements
🔹 Integrating LSTM and other deep learning models
🔹 Enhancing feature engineering for better accuracy
🔹 Exploring hybrid models combining ARIMA with neural networks

---

## 📧 Contact
📩 **Author:** Nishat Jillani  
📞 **Phone:** (+49) 017645964826  
📧 **Email:** nishatjillani631@gmail.com  
🌐 **LinkedIn:** [Nishat Jillani](https://www.linkedin.com/in/nishat-jillani-63b7b7211/)  
🏠 **Location:** Universitätsstr. 11/310-1, 03046 Cottbus, Germany  

> "Predicting the future is impossible, but making informed decisions is an art."

---

