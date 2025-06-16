# ☁️ AI-Driven Cloud Data Migration Framework

An intelligent, secure, and efficient framework for cloud data migration leveraging AI techniques such as NLP, graph algorithms, AI-ETL, reinforcement learning (RL), and anomaly detection. Designed to address the complexity of real-world data migration scenarios, this project integrates multiple AI modules to enhance data security, observability, dependency management, and performance during cloud migration to MongoDB Atlas.

---

## 📌 Project Title
**Data Migration in the Cloud Database with AI-Based Optimization for Security and Efficiency**

---

## 🧠 Abstract

This project introduces an integrated AI-powered framework that automates and optimizes secure cloud database migration. The system applies a combination of AI techniques to support every stage of the migration pipeline, including dependency mapping, schema transformation, anomaly detection, encryption, and resource optimization. Real-time and synthetic data were migrated to MongoDB Atlas using Python and libraries like NetworkX, Keras, and RL agents. The system successfully identified and resolved dependency cycles, encrypted high-sensitivity data, dynamically sized migration batches, and detected performance anomalies under simulated latency.

---

## ⚙️ Technologies & Tools

- **Languages:** Python 3  
- **Libraries:** NetworkX, Tensorflow/Keras, Pymongo, Gymnasium, Matplotlib, Numpy, Pandas, Cryptography  
- **Target Database:** MongoDB Atlas  
- **Platform:** Google Colab  
- **API:** Alpha Vantage (for real-time stock data)  

---

## 🚀 Key Features

### 🔍 Stage 1: Data Discovery & Dependency Mapping
- Uses **NLP** and **graph-based AI** (NetworkX) to identify and visualize relationships between entities.
- Automatically detects and breaks dependency cycles via topological sort and edge removal.

### 🛠️ Stage 2: Automated Data Transformation
- Applies **AI-ETL** for schema validation and transformation.
- Handles structured and unstructured formats.

### 🔐 Stage 3: Security & Compliance
- Implements **sensitivity-aware encryption**.
- Real-time **anomaly detection** using a binary classification model.
- Aligns with regulations like **GDPR** and **HIPAA**.

### 📈 Stage 4: Performance Optimization
- Uses **Reinforcement Learning (DQN agent)** to determine optimal batch sizes.
- Simulates latency, bandwidth, and dynamically adjusts batch strategy.

---

## 📊 Datasets

1. **Synthetic User Data** – 500 records with random dependency links and sensitivity classification.
2. **Real-Time Stock Data** – Retrieved from Alpha Vantage API (AAPL, GOOGL, MSFT, TSLA, AMZN).
3. **Fallback Stock Data** – Synthetic stock data generation used when API fails.

---

## 📋 Performance Results

| Metric                | Synthetic Users | Stock Prices |
|-----------------------|-----------------|--------------|
| Total Records         | 500             | 500          |
| RL Batch Size         | 5               | 5            |
| Avg Latency (ms)      | 28.59           | 16.45        |
| Anomalies Detected    | 40              | 3            |
| Dependency Cycles     | Yes (resolved)  | No           |

---

## 📈 Visualizations

- 📊 **Dependency Aggregation Graphs** (highlighting hubs and sensitive links)
- 📉 **Latency vs Anomaly Plots**
- 📈 **Stock Price Trend with Sensitive Points Highlighted**
- 📑 **Console Logs** showing batch size, anomaly detection, and encryption status

---

## 🔒 Challenges & Limitations

- Static threshold in anomaly detection can underperform in dynamic environments.
- RL scalability across heterogeneous infrastructure remains limited.
- High computational load when scaling unsupervised models with encryption.

---

## 🔮 Future Work

- Implement **hybrid anomaly detection** combining supervised and unsupervised learning.
- Deploy **dynamic thresholding** via **Reinforcement Learning (Q-learning or SARSA)**.
- Extend to **multi-cloud platforms** with real-time latency-aware migration.

---

## 🏫 Course Info

- **Course**: Advanced Database Topics (COMP 8157)  
- **Instructor**: Dr. Shafaq Khan  
- **Institution**: University of Windsor  
- **Semester**: Winter 2025  
- **Section**: 01  

---

## 📜 License

This project is for academic and research purposes only. Unauthorized use for commercial deployment is prohibited.

