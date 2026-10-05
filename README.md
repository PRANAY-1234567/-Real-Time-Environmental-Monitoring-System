# 🌱 Real-Time Environmental Monitoring System

A real-time environmental monitoring system built using **ESP32, sensors, Python, and Firebase** to collect, validate, store, and analyze environmental parameters.

## 📌 Project Overview

The system collects real-time environmental data using sensors connected to an ESP32. The collected readings are transmitted to **Firebase** for historical storage and monitoring.

Python is used for **data processing, validation, and analysis**. The project also focuses on identifying inconsistent sensor readings and troubleshooting data-flow issues to improve data reliability.

## 🎯 Objectives

* Collect environmental parameters in real time.
* Validate sensor readings and identify inconsistent values.
* Store historical sensor data in Firebase.
* Process and analyze collected data using Python.
* Troubleshoot sensor and data-flow issues.
* Provide a reliable approach for monitoring environmental conditions.

## 🛠️ Technologies Used

* **ESP32** – Microcontroller and sensor interfacing
* **Python** – Data processing and analysis
* **Firebase** – Real-time database and historical data storage
* **DHT11** – Temperature and humidity monitoring
* **MQ135** – Air-quality-related parameter monitoring
* **TM1637 Display** – Real-time parameter display
* **Buzzer & LEDs** – Environmental status indication
* **Arduino IDE** – ESP32 programming

## ⚙️ System Workflow

```text
Sensors
   ↓
ESP32
   ↓
Data Collection
   ↓
Data Validation
   ↓
Firebase
   ↓
Historical Data Storage
   ↓
Python
   ↓
Data Processing & Analysis
```

## 📊 Parameters Monitored

The system monitors environmental parameters such as:

* 🌡️ Temperature
* 💧 Humidity
* 🌫️ Air-quality-related readings

The collected values can be displayed in real time and stored for historical analysis.

## 🔍 Data Processing & Validation

The project includes basic data-quality checks to improve the reliability of collected sensor data.

Key activities include:

* Checking incoming sensor readings.
* Identifying inconsistent or unexpected values.
* Validating collected data before analysis.
* Processing historical data using Python.
* Troubleshooting communication and data-flow issues.
* Verifying that sensor data is correctly transferred and stored.

## ☁️ Firebase Integration

Firebase is used to store sensor readings and maintain historical environmental data.

This allows the system to:

* Store real-time readings.
* Maintain historical records.
* Retrieve data for further analysis.
* Monitor data flow between the ESP32 and database.

## 🐍 Python Analysis

Python is used to process and analyze the collected environmental data.

Typical tasks include:

* Reading stored sensor data.
* Cleaning and processing data.
* Checking data consistency.
* Analyzing environmental trends.
* Preparing data for further visualization or prediction.

## 🚀 Key Features

* Real-time environmental monitoring
* Sensor data collection using ESP32
* Data validation and quality checking
* Firebase-based historical data storage
* Python-based data processing
* Troubleshooting of data-flow issues
* Real-time display and alert indication

## 📁 Project Structure

```text
Real-Time-Environmental-Monitoring/
│
├── ESP32/
│   └── sensor_monitoring.ino
│
├── Python/
│   ├── data_processing.py
│   └── data_analysis.py
│
├── Documentation/
│   └── project_report.pdf
│
└── README.md
```

## 🔮 Future Improvements

* Add a web-based monitoring dashboard.
* Implement automated anomaly detection.
* Improve sensor-data validation.
* Add more environmental sensors.
* Implement advanced prediction models.
* Add automated alerts for abnormal readings.

## 👨‍💻 My Role

My role mainly involved **sensor integration, data collection, data validation, processing, testing, and troubleshooting**. I worked on checking sensor outputs, identifying inconsistent readings, and verifying the flow of data from the ESP32 to Firebase.

## 📜 Project Presentation

The project was presented at **ICASTII-2026** and further documented as a research publication.

---

⭐ **If you find this project useful, feel free to explore the repository and provide feedback.**

<img width="4160" height="3120" alt="WhatsApp Image 2026-10-06 at 2 09 26 AM" src="https://github.com/user-attachments/assets/235e3cc2-6f2b-4583-a0e0-ff14bd5a6a11" />

<img width="1033" height="549" alt="WhatsApp Image 2026-10-06 at 2 08 54 AM" src="https://github.com/user-attachments/assets/6224988e-0dee-4152-86d3-df7719313fd1" />

<img width="3120" height="4160" alt="WhatsApp Image 2026-10-06 at 2 08 54 AM" src="https://github.com/user-attachments/assets/4d316a6c-3a72-47e1-86d9-efa3c391715e" />
