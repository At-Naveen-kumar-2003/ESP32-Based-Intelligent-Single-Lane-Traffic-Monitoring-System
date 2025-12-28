# ESP32-Based Intelligent Single-Lane Traffic System Using LoRa

## 📌 Project Overview
This project implements an intelligent traffic management system for single-lane roads using **ESP32** and **LoRa** communication.  
Two identical nodes are installed at both ends of a narrow road. Each node detects vehicle entry/exit, communicates wirelessly using LoRa, and displays real-time lane status on an LCD.

The system prevents opposite-direction vehicle conflicts and improves safety without using the internet or cellular networks.

---

## 🎯 Objectives
- Prevent vehicle collisions on single-lane roads
- Display real-time vehicle count on both sides
- Enable long-range, low-power wireless communication
- Provide an internet-independent traffic control solution

---

## 🧠 System Architecture
- **Node A (Side A)**  
  Detects vehicle entry/exit and updates lane status
- **Node B (Side B)**  
  Receives updates and synchronizes vehicle count
- Both nodes act as **sender + receiver**
- Both sides display identical lane information

---

## ⚙️ Hardware Components
- ESP32 Development Board (2 units)
- LoRa Module (SX1278 / RA-02) – 433 MHz
- 16×2 I2C LCD Display (2 units)
- IR Sensors / Push Buttons (Entry & Exit)
- Connecting Wires
- Power Supply (USB / Battery)

---

## 🔌 Communication Technology
- **LoRa (Long Range Communication)**
  - Frequency: 433 MHz
  - Long-range (up to several kilometers)
  - Low power consumption
  - No internet required

---

## 🖥️ Display Information
Each LCD shows:
- Lane Status (FREE / BUSY)
- Number of vehicles currently inside the lane

Example:
