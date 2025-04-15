# 🤖 AI-Powered ML Pipeline Monitoring & Optimization

This capstone project showcases how Generative AI can be used to enhance MLOps and proactively monitor ML pipelines. Built using a real-world **Machine Failure Prediction** dataset, the solution integrates anomaly detection, automated reporting, and Retrieval-Augmented Generation (RAG) to support ML engineers in identifying and resolving issues efficiently.

---

## 🚀 Project Overview

- **Project Title:** AI-Powered ML Pipeline Monitoring & Optimization  
- **Use Case:** Predictive Maintenance + GenAI for Monitoring  
- **Course:** Generative AI Capstone  
- **Tools Used:** Python · Pandas · Scikit-learn · Prophet · LangChain · ChromaDB · Gemini API · Streamlit (optional)

---

## 📌 Key Features

### ✅ ML Monitoring & Anomaly Detection
- Tracks real-time performance of a predictive ML pipeline
- Detects anomalies in predictions, accuracy, or failure trends

### 🧠 GenAI Agent Integration
- Uses Gemini with LangChain or LangGraph
- Agent decides whether to:
  - Generate a summary report
  - Retrieve past anomaly logs (RAG with ChromaDB)
  - Trigger engineer alert

### 📈 Forecasting & Failure Insights
- Time series modeling using Prophet
- Failure cause prediction using classification models

### 🛠️ MLOps Simulation
- Logs, tracks, and summarizes simulated ML pipeline events
- Includes failure injection and auto-summary generation

---

## 📊 Dataset

- **Source:** [Kaggle - Machine Failure Prediction Dataset](https://www.kaggle.com/datasets/erhanleboglu/machine-failure-prediction)
- Contains sensor data from manufacturing machines
- Labeled with different types of machine failures

---

## 🧩 Project Structure
📁 ai-pipeline-monitoring/ ├── ai-powered-ml-pipeline-monitoring-optimization.ipynb # Main Kaggle notebook ├── pipeline_logs.json # Simulated ML logs ├── failure_summary.md # GenAI-generated summaries ├── chromadb/ # Local vector store for RAG │ └── index/ # Embeddings and metadata ├── models/ │ └── xgb_failure_predictor.pkl # Trained ML model ├── agents/ │ └── monitoring_agent.py # LangChain / LangGraph agent logic ├── utils/ │ └── log_utils.py # Logging + anomaly functions │ └── forecasting.py # Time series prediction helpers ├── app/ (optional) # Optional Streamlit UI │ └── main.py ├── requirements.txt # Dependencies └── README.md # This file
