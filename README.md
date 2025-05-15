# 📈 Predicting Stock Trends using CNN-LSTM Hybrid Model

This project demonstrates a deep learning approach for predicting stock price trends by integrating **Convolutional Neural Networks (CNN)** and **Long Short-Term Memory (LSTM)** models. The objective is to capture both spatial patterns and temporal dependencies in historical stock market data to make reliable forecasts.

Developed using Python and deep learning libraries, this project is ideal for use cases in financial analytics, algorithmic trading research, and machine learning model development.

## 🔍 Key Features

- 🔄 Retrieves real-time historical stock data using `yfinance`
- 📊 Data preprocessing with MinMaxScaler for normalization
- 🧠 Combines CNN and LSTM layers for better pattern recognition in time-series data
- 🧪 Model evaluation using MAE, MSE, and R² score
- 📈 Visualizes predicted vs. actual stock closing prices

## 📁 Project Structure
Predicting-Stock-Trends/
├── notebooks/
│ └── PROJECT CODE.ipynb # Main Jupyter Notebook
├── requirements.txt # Project dependencies
├── README.md # Project overview and usage
├── .gitignore # Files to ignore in Git
└── LICENSE # (Optional) License file


## ⚙️ Tech Stack

- Python
- Keras / TensorFlow
- NumPy, Pandas
- Scikit-learn
- yfinance
- Matplotlib

### 🔧 Prerequisites

- Python 3.7+
- Jupyter Notebook

📊 Model Overview
The CNN layers extract important patterns in stock price movements, while the LSTM layers model the time-dependent behavior. The hybrid model outputs future closing price predictions, which are then plotted against actual values for visual evaluation.

✅ Evaluation Metrics Used:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score

📷 Sample Output
Plot of Actual vs Predicted Closing Prices
(Note: Include a screenshot in your GitHub repo to visualize this)

👤 Author
Sejal Kumari
Final Year B.Tech CSE | Passionate about Machine Learning & Data Science
