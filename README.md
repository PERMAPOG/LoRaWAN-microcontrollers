# 🟢 LoRaWAN-Enabled Microcontroller Trash Monitoring System

This project powers an **IoT Trash Telemetry Monitoring (TTM) system** using **LoRaWAN microcontrollers** (HTC-AB01v2, HTC-AB02) and **ultrasonic sensors** to **remotely monitor fill levels of trash bins**. Data is transmitted to a **Chirpstack LoRaWAN server** for cloud-based visualization and analysis.

---

## 📌 Project Highlights
- 📡 **LoRaWAN Connectivity**: Efficient, long-range data transmission.
- 🖥️ **Cloud-Connected**: Integrated with **Chirpstack** running on **Docker**.
- 🧹 **Environmental Impact**: Optimizes waste collection, reduces overflows, cuts down operational costs.
- 🎛️ **Low-Power Setup**: Uses **HTC-AB01v2/AB02 boards** with **HC-SR04 Ultrasonic Sensor** and **MT3608 DC-DC booster** for energy efficiency.
- 🛠️ **Rapid Development**: Easily programmable via **Arduino IDE**.

---

## 📷 System Architecture Diagram
> _Optional but highly recommended_: Add a simple diagram made in draw.io or diagrams.net showing:
> Sensor → LoRa Node → Gateway → Chirpstack Server → Dashboard
>
> ![circuit_wiring](https://github.com/user-attachments/assets/f7a3affd-5ec3-4250-bf0b-a2cba2337916)

---

## 🚀 Quick Start Guide

### ✅ Prerequisites
- Arduino IDE installed
- Board-specific drivers for HTC-AB01v2/AB02
- LoRaWAN **Device EUI** and **App Key**
- Chirpstack LoRaWAN Server (Docker)

