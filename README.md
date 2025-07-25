# 🐝 Anomaly Detection in Beehive Environmental Data: Autoencoder and ML Methods

![Project Banner](https://raw.githubusercontent.com/snsamia/Anomaly-Detection-in-Beehive-Environmental-Data-Autoencoder-ML-Methods-/main/beehive_project_banner_fancy.png)

A comprehensive anomaly detection system for beehive environmental data using both traditional machine learning (One-Class SVM, Isolation Forest) and deep learning (Autoencoder) techniques.
The project leverages real-world sensor data to identify abnormal patterns in temperature and humidity, providing valuable insights for precision beekeeping and IoT-based environmental monitoring

---

## 🔍 Project Overview

- **Dataset**: Real-world sensor data from a monitored beehive (temperature, humidity)
- **Source**: [Kaggle Dataset - Beehives](https://www.kaggle.com/datasets/vivovinco/beehives/data)
- **Traditional ML Models**:
  - One-Class SVM
  - Isolation Forest
- **Deep Learning**:
  - Autoencoder for unsupervised anomaly detection
- **Output**: Anomalous data points based on reconstruction error and model decision boundaries

---

## 📈 Sample Output

- 📊 MSE histogram to visualize reconstruction errors  
- 🎯 Contour plots to show anomaly decision regions  
- 🧠 Thresholding (95th percentile) to identify anomalies

---

 ##  🛠️ Future Improvements
 
- LSTM Autoencoder for time series anomaly detection
- Deploy as a Streamlit app
- Connect to real-time IoT data streams



