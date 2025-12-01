# 🔌 OptiWatt – IoT-Based Smart Energy Management System

OptiWatt is a cost-effective IoT smart energy management solution designed to optimize power consumption in residential single-room environments.  
The system integrates **real-time energy monitoring**, **occupancy-aware automation**, and a **web-based control interface** to reduce unnecessary energy usage while preserving user control.

This repository contains:
- 📄 Project Proposal (PDF)
- 📄 Final Project Report (PDF)
- 🧪 Source code for ESP32
- 🖥️ Web interface files (if applicable)

---

## 📘 Abstract
OptiWatt is a practical and affordable smart energy solution built for residential settings, especially in developing regions where commercial systems are costly.  
The system uses an **ESP32 microcontroller** as the core unit, paired with:
- **PZEM-004T** for accurate real-time voltage, current, and power measurement  
- **Dual HC-SR04 ultrasonic sensors** for occupancy detection and people counting  

Based on room occupancy, OptiWatt **automatically disconnects non-critical loads** while still allowing manual override through a web dashboard.  
The implemented prototype demonstrates how low-cost hardware can deliver **energy efficiency**, **automation**, and **privacy-preserving monitoring** without relying on cameras or cloud services.

---

## 🚀 Features
- ⚡ Real-time power monitoring using PZEM-004T  
- 👥 Occupancy detection with ultrasonic sensors  
- 🔄 Automatic load switching based on room activity  
- 🌐 Local web interface for manual override and visualization  
- 🔐 Privacy-friendly (no cameras used)  
- 💰 Low-cost hardware design suitable for developing regions  

---

## 🏗️ System Architecture
- **ESP32** – central processing and WiFi connectivity  
- **PZEM-004T** – power measurement module  
- **HC-SR04 sensors** – bidirectional people counting  
- **Relay Module** – controls non-critical loads  
- **Web Dashboard** – shows energy data and allows override  

---


---

## 👨‍💻 Authors
- *(Team Phase-Shift)*  
- Department of CSE / *(United International Unversity)*  

---

## ⭐ Support
If you like this project, please give the repo a **star ⭐** — it helps others find it!


