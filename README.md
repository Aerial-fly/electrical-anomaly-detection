# Hourly Electricity Consumption Anomaly Detection (AEP) ⚡

This project aims to detect anomalies in time-series electricity consumption data using the American Electric Power (AEP) dataset from PJM Interconnection.

## 🎯 Objective
Compare the performance of two different algorithms in detecting abnormal electricity usage:
1. **Isolation Forest** (Machine Learning - Unsupervised)
2. **LSTM Autoencoder** (Deep Learning - Neural Network)

## 🛠️ Technologies Used
* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **Scikit-Learn** (for Isolation Forest & Preprocessing)
* **TensorFlow/Keras** (to build the LSTM architecture)

## 📊 Analysis Results
* **Isolation Forest:** Highly effective in detecting *Global Outliers* (extremely high/low electricity load values).
* **LSTM Autoencoder:** More sensitive to *Contextual Anomalies* (unusual spike patterns based on the previous 30 hours).
* **Intersection:** An intersection anomaly was found indicating the most critical conditions (Extreme Values ​​+ Strange Patterns).

## 📈 Visualization
This project produces an interactive comparison graph and Venn Diagram to map the agreement between the two models.

---
*Created as a research Project by Aerial.*
