📈 Time Series Anomaly Detection using Stock Market Data
🔍 Project Overview

This project focuses on detecting anomalies in stock market time series data of Reliance Industries using statistical and machine learning techniques.

Historical daily stock data (last 5 years) is dynamically downloaded from:

📊 Yahoo Finance

The project demonstrates a complete end-to-end data science pipeline:

Data Collection → EDA → Statistical Detection → ML Detection → Visualization → Financial Interpretation 🚀

🎯 Objective

Identify abnormal price movements

Detect unusual trading volume spikes

Compare statistical vs ML-based anomaly detection

Interpret financial significance of detected anomalies

📊 Dataset Features

The dataset includes:

Date

Open

High

Low

Close

Volume

Data is fetched dynamically using yfinance.

📌 Data Understanding

OHLC structure analyzed

Trading volume interpreted as market participation indicator

Date converted to datetime format

Data sorted chronologically

📈 Exploratory Data Analysis (EDA)

Closing Price Time Series Plot

Volume Time Series Plot

Daily Return Calculation

Return Distribution Analysis

Rolling Volatility Analysis

Identification of spikes and crash periods

🧪 Anomaly Detection Methods
🔹 Statistical Methods

Z-Score Method

IQR Method

Moving Average Deviation

🔹 Machine Learning Methods

Isolation Forest

One-Class SVM

Anomalies were detected in:

Closing Price

Trading Volume

Daily Returns

📊 Evaluation & Visualization

Anomalies highlighted on time series charts

Comparison of anomaly counts across methods

Overlap analysis between price & volume anomalies

Top 10 extreme return days identified

🧠 Financial Interpretation

Detected anomalies were analyzed in context of potential real-world events such as:

Market crashes

Earnings announcements

Economic policy changes

High volatility periods

🛠 Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

yFinance

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/time-series-anomaly-detection.git


Navigate into project:

cd time-series-anomaly-detection


Install dependencies:

pip install -r requirements.txt


Run the script:

python src/anomaly_detection.py

📌 Key Learnings

Time series preprocessing

Financial return modeling

Statistical outlier detection

Unsupervised ML anomaly detection

Interpretation of financial data anomalies

👨‍💻 Author

Abhishek Shelke
MSc Computer Science | Aspiring ML Engineer

GitHub: https://github.com/Redskull2525
