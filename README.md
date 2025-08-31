# DabbleESP32

![Version](https://img.shields.io/badge/version-1.5.2-blue.svg)  
![Last Updated](https://img.shields.io/badge/updated-August%202025-brightgreen.svg)  
![Platform](https://img.shields.io/badge/platform-ESP32-orange.svg)  
![License](https://img.shields.io/badge/license-MIT-lightgrey.svg)  

DabbleESP32 is an **Arduino library** that brings the power of the [Dabble mobile app](https://thestempedia.com/product/dabble/) to ESP32 boards.  
It allows you to control and communicate with your ESP32 wirelessly over **Bluetooth Classic** using your smartphone.  

With DabbleESP32, you can easily integrate your ESP32 projects with modules such as:

- 🎮 **Gamepad** – Control robots, cars, or drones using joysticks and buttons.  
- 📱 **Phone Sensors** – Access accelerometer, gyroscope, magnetometer, and GPS data.  
- 💻 **Terminal** – Send and receive text data between your phone and ESP32.  
- 📸 **Camera Control** – Trigger and control phone camera functions.  
- 🌐 **IoT Dashboard** – Monitor and interact with sensors and actuators.  

---

## ✨ Features
- Simple API designed for Arduino IDE and PlatformIO.  
- Supports **Bluetooth Serial (Classic)** on ESP32.  
- No extra hardware required — just install the app and pair your ESP32.  
- Lightweight and efficient for real-time projects.  

---

## 📲 Requirements
- ESP32 development board  
- [Dabble mobile app (Android/iOS)](https://thestempedia.com/product/dabble/)  
  - [Download on Android (Google Play)](https://play.google.com/store/apps/details?id=io.dabbleapp)  
  - [Download on iOS (App Store)](https://apps.apple.com/us/app/dabble-bluetooth-controller/id1472734455)  
- Arduino IDE (v1.8.19 or later) or PlatformIO  

---

## 🚀 Getting Started

### 1. Install Library
- Clone this repo into your Arduino `libraries` folder, or install via PlatformIO.  

### 2. Include in Your Sketch
```cpp
#include <DabbleESP32.h>
