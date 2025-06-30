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

![image](https://github.com/user-attachments/assets/48ea4489-7567-46f3-8cb0-b54b0496b6f4)


### 📈 Main Features:
- Detects **aggressive accelerations**, **harsh braking**, and **sharp turns**
- Computes a **driving score** in real-time based on sensor data
- Transmits measurements wirelessly over **Bluetooth**
- Supports parameter tuning via serial interface

---

## 📂 Files Included

- `ES2324_Gonçalo_Measure_Quality_Driving_Report.pdf`  
  ⤷ Full project report with methodology, schematics, and implementation

- `Updated_Risk_Assessment.xlsx`  
  ⤷ Risk analysis and mitigation plan for the embedded system

---

## 🛠️ Implementation Notes

- System samples acceleration and angular velocity from the MPU6050.
- Thresholds for events (e.g. harsh brake at < -1.5 m/s²) are configurable.
- Driving score decreases with each detected event, providing feedback.
- Evaluation was based on multiple criteria: implementation quality, clarity of documentation, usability, and robustness.

---

## 👨‍🎓 Author

- **Gonçalo Tavares Bastos** – eusoudebastos@gmail.com
📅 Submitted: June 2024

---

## 📝 Notes

This project is a simplified proof-of-concept meant for educational use, and does not replace certified vehicle telematics solutions.

