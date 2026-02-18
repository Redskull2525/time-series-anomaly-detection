

# 📈 Time Series Anomaly Detection using Stock Market Data

## 🔍 Overview

This project focuses on detecting anomalies in historical stock market time series data of **Reliance Industries** using both statistical and machine learning techniques.

Daily stock data (last 5 years) is dynamically fetched from:

📊 Yahoo Finance

The project demonstrates a complete end-to-end data science workflow:

> **Data Collection → EDA → Statistical Detection → ML Detection → Visualization → Financial Interpretation**

---

## 🎯 Problem Statement

Financial markets experience abnormal price movements and unusual trading volume spikes due to:

* Earnings announcements
* Market crashes
* Economic policy changes
* Global news events

The objective of this project is to:

* Identify abnormal price behavior
* Detect unusual trading volume patterns
* Compare statistical vs machine learning-based anomaly detection
* Interpret potential financial significance of anomalies

---

## 📊 Dataset Details

Data Source: Yahoo Finance
Stock: Reliance Industries (RELIANCE.NS)
Time Range: Last 5 Years (Daily Frequency)

### Features Used:

* Date
* Open
* High
* Low
* Close
* Volume

Data is fetched dynamically using `yfinance`, ensuring reproducibility without storing raw datasets in the repository.

---

## 📌 Data Preprocessing

* Converted Date column to datetime format
* Sorted data chronologically
* Calculated Daily Returns
* Computed 20-day Rolling Volatility
* Handled missing values

---

## 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Closing Price Time Series Visualization
* Trading Volume Trend Analysis
* Daily Return Distribution
* Volatility Pattern Analysis
* Identification of visually noticeable spikes and crash periods

---

## 🧪 Anomaly Detection Techniques

### 🔹 Statistical Methods

1. **Z-Score Method**
   Detects outliers beyond a selected standard deviation threshold.

2. **IQR (Interquartile Range) Method**
   Identifies extreme return values outside the interquartile range.

3. **Moving Average Deviation**
   Flags abnormal deviations from rolling mean.

---

### 🔹 Machine Learning Methods

1. **Isolation Forest**

   * Unsupervised learning algorithm
   * Isolates anomalies based on random tree splits
   * Effective for high-dimensional anomaly detection

2. **One-Class SVM**

   * Learns normal data boundary
   * Detects deviations as anomalies

---

## 📊 Evaluation & Comparison

* Compared number of anomalies detected by each method
* Highlighted anomalies on price time series plots
* Analyzed overlap between price and volume anomalies
* Identified Top 10 extreme positive and negative return days

---

## 🧠 Financial Interpretation

Detected anomalies were analyzed for potential causes such as:

* Market-wide corrections
* High volatility phases
* Policy announcements
* Sector-specific movements

This bridges technical detection with real-world financial reasoning.

---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* yFinance

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Redskull2525/time-series-anomaly-detection.git
```

### 2️⃣ Navigate to Project Folder

```bash
cd time-series-anomaly-detection
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Script

```bash
python src/anomaly_detection.py
```

---

## 📌 Key Learning Outcomes

* Time Series Data Handling
* Financial Return Modeling
* Statistical Outlier Detection
* Unsupervised Machine Learning
* Model Comparison & Interpretation
* End-to-End Data Science Pipeline Implementation

---

## 🔮 Future Improvements

* Add interactive dashboard (Streamlit)
* Integrate deep learning Autoencoder
* Perform anomaly clustering analysis
* Add event-based financial news mapping

---

## 👨‍💻 Author

**Abhishek Shelke**
MSc Computer Science | Aspiring Machine Learning Engineer

GitHub: [https://github.com/Redskull2525](https://github.com/Redskull2525)
LinkedIn: [https://www.linkedin.com/in/abhishek-s-b98895249](https://www.linkedin.com/in/abhishek-s-b98895249)
