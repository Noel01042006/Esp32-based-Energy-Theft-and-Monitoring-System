# Esp32-based-Energy-Theft-and-Monitoring-System

An IoT-based real-time energy monitoring and theft detection system using ESP32 and dual PZEM-004T energy measurement modules. The system performs edge-based anomaly detection by comparing supply-side and load-side current to detect unauthorized power usage.

## 🚀 Features

- Dual-point energy monitoring
- Real-time anomaly detection
- Edge-based processing (no cloud dependency)
- Firebase cloud integration
- Live monitoring dashboard (PWA)
- Sub-second response latency
- >98.5% detection accuracy

---

## 🧠 System Architecture

Supply Line → PZEM Sensor 1 → ESP32 → Comparison Logic  
Load Line → PZEM Sensor 2 → ESP32 → Anomaly Detection  

If difference > threshold → Theft Detected

---

## 🔧 Hardware Components

- ESP32 Dev Board
- 2 × PZEM-004T Energy Monitoring Modules
- Voltage/Current Input Lines
- Power Supply
- WiFi Network

---

## ⚙️ Working Principle

The system measures:

- Input power (supply side)
- Output power (load side)

If Supply Current - Load Current > Threshold:

Then:

→ Energy theft detected  
→ Alert triggered  
→ Data logged to Firebase  

---

## 📡 Cloud Integration

- Firebase Realtime Database
- Web Dashboard (PWA)
- Live monitoring
- Historical data logging

---

## 📊 Performance

- Detection Accuracy: >98.5%
- Response Time: <500 ms
- Real-time monitoring
- Stable continuous operation

---

## 📁 Repository Structure
firmware/ → ESP32 code
hardware/ → circuit + block diagram
dashboard/ → web app details
docs/ → architecture documentation

---

## 🛠️ Technologies Used

- ESP32
- PZEM-004T
- Firebase
- IoT
- Edge Computing
- Embedded C
- Arduino Framework

---

## 🎯 Applications

- Smart Grid Monitoring
- Industrial Power Monitoring
- Home Energy Security
- Utility Theft Detection
- Distribution Network Monitoring

---

## 👨‍💻 Author

Noel Varghese George  
Electronics & Communication Engineering  
TKM College of Engineering  

LinkedIn: https://linkedin.com/in/noel-varghese-george-a44333328  
GitHub: https://github.com/Noel01042006
