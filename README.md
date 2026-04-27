# 🐎 Horse Health Monitoring System (IoT)

A hardware + software system for **real-time monitoring of horse health**, using Arduino, sensors, and a mobile interface.

---

## 🚀 Overview

This project implements a **smart monitoring device** that tracks the physical condition of a horse continuously (24/7) and sends the data to a smartphone.

The system measures:

- Heart rate ❤️  
- Activity / movement 🏃  

and transmits the data via **Bluetooth** to a mobile app, allowing the owner to monitor the horse remotely.

---

## 💡 Motivation

Horses are valuable animals and vulnerable to diseases such as:

- Influenza  
- Colic  
- Tetanus  

Without continuous monitoring, these conditions can go unnoticed.

This project aims to:
- Detect abnormal health conditions early  
- Reduce risks and costs  
- Provide constant supervision without manual effort  

---

## 🧩 System Architecture

### 🔌 Hardware Components

- Arduino UNO (R3)
- Pulse Sensor (heart rate)
- Accelerometer (ADXL345)
- Bluetooth module (HC-05)
- LED (status indicator)
- Breadboard + jumper wires

---

### 📡 Data Flow

Sensors → Arduino → Bluetooth → Mobile App (Blynk)

- Sensors collect physiological data  
- Arduino processes signals  
- Data is sent via Bluetooth  
- User views results on smartphone  

---

## ⚙️ Features

### 📊 Real-Time Monitoring

- Heart rate tracking  
- Movement/activity detection  
- Continuous (24/7) monitoring  

---

### 📱 Mobile Interface (Blynk)

The Android app provides:

- Live sensor data display  
- Bluetooth connection control  
- LED control (on/off)  
- Simple UI (Persian)

---

### 🚨 Alert Mechanism

- If health parameters exceed normal thresholds:
  - LED turns ON  
  - User can be notified  

---

### 🧠 Activity Detection

Using accelerometer data:
- Standing  
- Walking  
- Running  

---

## 🔬 Implementation Details

### ❤️ Heart Rate Sensor

- Connected to analog pin  
- Counts pulses over time  
- Sends data to mobile app  

### 🏃 Accelerometer

- Measures motion in X/Y/Z axes  
- Samples data periodically  
- Detects activity level  

### 🔵 Bluetooth Communication

- Uses HC-05 module  
- Serial communication with Arduino  
- Connected to Blynk app  

---

## 🧪 Results

The system successfully:

- Monitors horse health continuously  
- Sends real-time data to smartphone  
- Allows remote interaction with device  

---

## ⚠️ Limitations

- Bluetooth range is limited  
- Sensor accuracy depends on placement  
- No internet connectivity  

---

## 🚀 Future Improvements

- Replace Bluetooth with WiFi (ESP modules)  
- Add GPS tracking  
- Add training analytics  
- Improve sensor precision  

---

## 🧑‍💻 Authors

- Soha Niroomand  
- Atina Atoukesh  

Farzanegan 1 High School, Tehran  

---

## 💬 In One Sentence

A **smart IoT system for monitoring horse health in real-time using Arduino and mobile integration**.
