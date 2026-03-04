# NoSQL Log-Based Anomaly Detection System

## Overview
This project implements a machine learning–based system to detect abnormal patterns in system logs stored in a **MongoDB NoSQL database**. The system analyzes log data and automatically identifies suspicious activities that may indicate security threats, system failures, or unauthorized access.

The goal is to enable **automated security monitoring and anomaly detection** for large volumes of log data.

---

## Features
- Collects and analyzes system log data from MongoDB
- Preprocesses log data using Python and Pandas
- Converts categorical log attributes into numerical format using Label Encoding
- Uses **Isolation Forest** to detect anomalies in logs
- Classifies log entries as **Normal** or **Anomaly**
- Stores detected anomalies in a separate MongoDB collection
- Enables automated monitoring and security analysis

---

## System Architecture
1. Logs stored in MongoDB database
2. Python script retrieves logs
3. Data preprocessing using Pandas
4. Feature encoding using Label Encoder
5. Anomaly detection using Isolation Forest
6. Detected anomalies stored in MongoDB

---

## Technologies Used
- Python
- MongoDB
- Pandas
- NumPy
- Scikit-learn
- Isolation Forest

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/nosql-log-anomaly-detection.git
cd nosql-log-anomaly-detection
