# Telecom Churn Prediction — MLOps Pipeline

This project implements an **end-to-end MLOps pipeline** for predicting telecom customer churn. The objective is to operationalize machine learning models with robust training, deployment, and monitoring workflows, ensuring scalability, reproducibility, and reliability in production.

---

## Project Overview

The pipeline covers the full lifecycle of a machine learning model, from **data preparation and training** to **deployment and monitoring**. It integrates automation and experiment tracking to deliver a production-ready churn prediction system.

---

## Key Features

### **End-to-End MLOps Pipeline**
- Data preprocessing, feature engineering, and model training  
- Automated workflows for reproducibility and continuous improvement  

### **Model Deployment**
- Predictions served via **FastAPI REST API**  
- Interactive exploration with **Streamlit**  
- Fully containerized using **Docker**  

### **Automation**
- **Makefile** for standardized and simplified tasks  
- CI/CD-ready structure for seamless integration  

### **Experiment Tracking**
- Comprehensive logging of experiments, metrics, and parameters with **MLflow**  
- Versioned models and experiment storage  
- Automated **email and system notifications** during model lifecycle events  

### **Monitoring & Logging**
- **Elasticsearch + Kibana** for real-time system monitoring and log visualization  
- Tracking of infrastructure (CPU, memory, latency) and model performance (accuracy, precision, recall)  
- Alerts for anomalies and performance degradation  

---

## Tools & Technologies

- **FastAPI** — REST API for serving predictions  
- **Streamlit** — Web interface for visualization  
- **Docker** — Containerization for reproducible environments  
- **Makefile** — Task automation and simplified execution  
- **MLflow** — Experiment tracking and model registry  
- **Elasticsearch + Kibana** — Monitoring and log visualization  
- **Notification System** — Email and system alerts  
