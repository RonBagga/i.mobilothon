# 🚗 Brake Shoe Replacement Prediction – IoT & ML-Based Preventive Maintenance

Developed by **Team Learners**, this project presents an IoT-enabled smart monitoring system designed to proactively detect and predict brake pad wear in vehicles. Using real-time sensor data and machine learning, the system ensures timely maintenance alerts, reducing accidents and costly repairs.

## 🧠 Problem Statement

Frequent brake failures are among the top causes of road accidents. Traditional maintenance systems are reactive, addressing issues only after they occur, which increases risk, cost, and vehicle downtime. 

**Need:** A proactive, intelligent system that continuously monitors brake pad condition and alerts drivers before failures occur.

## 🎯 Project Objective

To develop an **IoT-powered Brake Pad Monitoring System** that:

- Continuously gathers real-time data from brake sensors  
- Predicts brake wear using a trained **Random Forest ML algorithm**  
- Sends early maintenance alerts to the vehicle dashboard  
- Transitions from reactive to **predictive maintenance**  
- Enhances **road safety, vehicle life**, and cost efficiency

---

## 🔍 Core Features

- **Real-Time Data Collection** from sensors:
  - Acoustic Sensor – captures abnormal sounds
  - ATE Brake Pad Sensor – monitors pad thickness
  - K-Type Thermocouple – detects overheating  
- **ML-Based Prediction** using Random Forest to estimate brake pad health
- **Alert System**: Visual and audio notifications sent to drivers
- **Cloud Storage**: For model updates and historical insights
- **IoT Gateway** using Arduino/ESP32 for sensor communication

---

## ⚙️ System Architecture

1. **Sensors** → Microcontroller (ESP32/Arduino)  
2. **IoT Gateway** → Data Aggregation & Preprocessing  
3. **Machine Learning Model** → Brake Wear Prediction  
4. **Alert System** → Dashboard Notification (Light/Beep)  
5. **Cloud Storage** → Data logging and future training

---

## 📊 Machine Learning Model

- **Algorithm**: Random Forest Classifier
- **Features Used**: 
  - Acoustic Frequency
  - Brake Pad Thickness
  - Brake Temperature
- **Data Processing**: Normalization, Noise Filtering
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score, RMSE
- **Model Deployment**: Serialized with `joblib` or `pickle`
- **Threshold Alerts**: Triggered when pad thickness drops below 20% or confidence > 80%

---

## 🧰 Tech Stack

### 🖧 Hardware
- Arduino / ESP32
- ATE Thickness Sensor
- Acoustic Sensor
- K-Type Thermocouple

### 🖥️ Software & Frameworks
- Python, Scikit-learn, NumPy, Pandas, Matplotlib
- Arduino IDE / PlatformIO
- Flask / FastAPI (backend APIs)
- MQTT / HTTP Protocols
- AWS IoT Core / Google Cloud IoT
- Firebase for Push Notifications (optional)

---

## 🔔 Alert System

Real-time alerts are delivered via:
- Dashboard blinking lights  
- Beeping sound signals  
- (Optional) Push Notifications to mobile or cloud apps

---

## 🧪 Future Scope

- Extend prediction system to monitor other vehicle parts (e.g., tires, engine belts)
- Integrate with commercial fleet management software
- Expand dataset and train deeper ML/DL models for improved accuracy

---

## 👨‍💻 Team Learners

- **Team Leader**: Ronit Bagga  
- **Team Members**: Rohan Chauhan  
- **Institution**: JIMS Engineering Management Technical Campus  
- **Project Title**: Brake Shoe Pad Replacement Prediction  

