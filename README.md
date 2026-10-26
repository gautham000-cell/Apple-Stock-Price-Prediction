# 🍎 Apple Stock Price Prediction & 30-Day Forecasting

> An AI-powered stock forecasting application that predicts future Apple (AAPL) stock prices using a deep learning GRU model and provides interactive visualizations through a Streamlit web application.

![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-FF4B4B?logo=streamlit)
![ONNX](https://img.shields.io/badge/Model-ONNX-005CED?logo=onnx)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📌 Overview

This project leverages Deep Learning and Time Series Forecasting to predict Apple's future stock prices based on historical market data.

The trained GRU model is optimized using ONNX Runtime for fast inference and deployed as an interactive Streamlit application where users can visualize historical trends and generate future predictions.

---

## 🚀 Features

- 📈 Historical Apple stock price visualization
- 🤖 GRU-based Deep Learning forecasting model
- 📅 30-Day future stock price prediction
- ⚡ Fast inference using ONNX Runtime
- 📊 Interactive Streamlit dashboard
- 🔄 Data preprocessing and normalization
- 📉 Trend visualization using Matplotlib
- 💾 Pre-trained model included for instant predictions

---

## 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Framework | Streamlit |
| Machine Learning | TensorFlow / Keras |
| Model Optimization | ONNX Runtime |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib |
| Model Serialization | Pickle |

---

## 📂 Project Structure

```text
APPLE-STOCK-PRICE-PREDICTION-FORECASTING-30-DAYS/
│
├── assets/
│   ├── multistep_gru.onnx
│   ├── multistep_scaler.pkl
│   ├── apple_df_cleaned.pkl
│   └── ...
│
├── streamlit_app.py
├── Apple_stock_Prediction.ipynb
├── requirements.txt
├── README.md
└── LICENSE
```

---

## ⚙ Installation

### Clone Repository

```bash
git clone https://github.com/Aparnarajes/APPLE-STOCK-PRICE-PREDICTION-FORECASTING-30-DAYS-.git

cd APPLE-STOCK-PRICE-PREDICTION-FORECASTING-30-DAYS-
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run streamlit_app.py
```

---

## 📊 Machine Learning Workflow

```
Historical Stock Data
          │
          ▼
Data Cleaning & Preprocessing
          │
          ▼
Feature Scaling
          │
          ▼
GRU Deep Learning Model
          │
          ▼
ONNX Conversion
          │
          ▼
30-Day Future Prediction
          │
          ▼
Interactive Streamlit Dashboard
```

---

## 📈 Prediction Pipeline

- Historical market data preprocessing
- Feature normalization
- Sequential time-series generation
- GRU model inference
- Recursive forecasting for the next 30 days
- Visualization of forecasted prices

---

## 🎯 Applications

- Financial Data Analysis
- Time Series Forecasting
- AI-Powered Stock Prediction
- Educational Machine Learning Projects
- Deep Learning Demonstration

---

## 📸 Application Preview

> Add screenshots of your Streamlit dashboard here.

Example:

```
assets/homepage.png
assets/prediction.png
assets/forecast.png
```

---

## 🔮 Future Improvements

- Support multiple stock symbols
- Live stock data integration
- LSTM & Transformer model comparison
- Technical indicators (RSI, MACD, EMA)
- Candlestick chart visualization
- News sentiment analysis
- Portfolio recommendation system
- Model retraining pipeline

---

## 📚 Skills Demonstrated

- Time Series Forecasting
- Deep Learning (GRU)
- Model Deployment
- Streamlit Development
- ONNX Runtime Optimization
- Data Visualization
- Feature Engineering
- Machine Learning Pipelines

---

## 👩‍💻 Author

**Aparna Rajesh**

Artificial Intelligence & Machine Learning Engineer

- GitHub: https://github.com/Aparnarajes
- LinkedIn: *Add your LinkedIn profile*

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates future improvements.

---

## 📄 License

This project is licensed under the MIT License.
