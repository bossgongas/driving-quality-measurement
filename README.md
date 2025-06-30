# 🚗 Driving Quality Measurement System – Arduino & MPU6050

This project was developed for the course **Engenharia de Sistemas (Systems Engineering)** during the academic year **2023/2024**,  
**Bachelor in Electrical and Computer Engineering – University of Coimbra**.

---

## 🎯 Objective

Design and prototype a **low-cost embedded system** to evaluate the **quality of vehicle driving** in real time. The solution uses an Arduino Uno, an MPU6050 accelerometer/gyroscope, and a Bluetooth module to detect, log, and analyze driving behavior.

---

## 🧱 System Overview

### 🔌 Components:
- **Arduino Uno**
- **MPU6050** (3-axis accelerometer + gyroscope)
- **HC-05 Bluetooth Module**
- Smartphone with **Serial Bluetooth Terminal** app (for data visualization)

### 📈 Main Features:
- Detects **aggressive accelerations**, **harsh braking**, and **sharp turns**
- Computes a **driving score** in real-time based on sensor data
- Transmits measurements wirelessly over **Bluetooth**
- Supports parameter tuning via serial interface

---

## 📂 Files Included

- `ES2324_Gonçalo_Measure_Quality_Driving_Report.pdf`  
  ⤷ Full project report with methodology, schematics, and implementation

- `EngSist2324-Practical_assignment_evaluation.pdf`  
  ⤷ Evaluation breakdown with system requirements and assessment criteria

- *(optional: Arduino code, wiring diagrams, test data, video demo, etc.)*

---

## 🛠️ Implementation Notes

- System samples acceleration and angular velocity from the MPU6050.
- Thresholds for events (e.g. harsh brake at < -1.5 m/s²) are configurable.
- Driving score decreases with each detected event, providing feedback.
- Evaluation was based on multiple criteria: implementation quality, clarity of documentation, usability, and robustness.

---

## 📱 How to Use

1. Upload code to Arduino Uno
2. Power device and connect via HC-05 Bluetooth to mobile app
3. Start driving and observe events and scores in the terminal

---

## 👨‍🎓 Author

- **Gonçalo Tavares Bastos** – Nº 2020238997  
📅 Submitted: June 2024

---

## 📝 Notes

This project is a simplified proof-of-concept meant for educational use, and does not replace certified vehicle telematics solutions.

