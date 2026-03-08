# Embedded-Heart-Rate-Monitoring-System-Using-Arduino-and-MAX30102-Sensor
This project implements a real-time heart rate monitoring system using an Arduino Uno R3, MAX30102 pulse sensor, and a 16×2 LCD display. The sensor detects blood flow changes to calculate heart rate (BPM), and the readings are displayed on the LCD, demonstrating embedded systems and sensor integration for basic health monitoring.
# ❤️ Heart Rate Monitoring System using Arduino and MAX30102

## 📌 Project Overview
This project presents the design and implementation of a Heart Rate Monitoring System using Arduino Uno R3, MAX30102 Pulse Oximeter Sensor Module, and a 16x2 I2C LCD Display.

The system measures the heart rate in Beats Per Minute (BPM) by detecting variations in blood flow using an optical sensor. The processed heart rate value is displayed in real time on the LCD screen.

This project demonstrates a practical implementation of embedded systems, sensor interfacing, and biomedical signal monitoring.

---

## 🛠 Components Used
- Arduino Uno R3
- MAX30102 Pulse Oximeter Sensor Module
- 16x2 LCD Display (I2C)
- Jumper wires
- Breadboard (optional)

---

## ⚙️ Circuit Connections

### MAX30102 → Arduino

| Sensor Pin | Arduino Pin |
|------------|-------------|
| VIN | 5V |
| GND | GND |
| SDA | A4 |
| SCL | A5 |

### LCD (I2C) → Arduino

| LCD Pin | Arduino Pin |
|---------|-------------|
| VCC | 5V |
| GND | GND |
| SDA | A4 |
| SCL | A5 |

---

## 📷 Circuit Diagram

![Circuit Diagram](images/device_photo.png)

---

## 🔬 Working Principle
1. The MAX30102 sensor emits infrared light into the fingertip.
2. Blood volume changes with each heartbeat.
3. The sensor detects reflected light variations caused by blood flow.
4. The microcontroller processes the signal to calculate heart rate.
5. The heart rate is displayed on the LCD screen in BPM.

---

## 🎯 Key Features
- Real-time heart rate monitoring
- Optical pulse detection
- LCD display for BPM output
- Simple and low-cost hardware design
- Easy integration with embedded systems

---

## 🚀 Applications
- Personal health monitoring devices
- Wearable fitness trackers
- Biomedical engineering experiments
- Remote patient monitoring systems
