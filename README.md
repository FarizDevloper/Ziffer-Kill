<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?center=true&lines=🔐+Smart+Security+Gate+System;ESP32+Smart+IoT+Pintu+Otomatis;Telegram+Control+%7C+Sensor+PIR+%7C+RFID+%7C+PDF+Log&font=Fira+Code&pause=1000&color=58A6FF&center=true&width=1000&height=50">
</p>

<h1 align="center">🔐 SmartGate ESP32 IoT System</h1>

<p align="center">
  <b>A fully-featured smart gate controller powered by ESP32</b><br>
  Telegram Bot integration | Motion Detection | Smoke Alarm | Current Monitoring | RFID Access
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ESP32-Microcontroller-blue.svg?logo=espressif">
  <img src="https://img.shields.io/badge/License-MIT-green.svg">
  <img src="https://img.shields.io/badge/Platform-Arduino%7CEspressif-lightgrey">
  <img src="https://img.shields.io/badge/Control-Telegram-blue.svg?logo=telegram">
  <img src="https://img.shields.io/badge/Access-RFID-orange.svg?logo=nfc">
  <img src="https://img.shields.io/badge/Alert-Smoke%20%7C%20Current-red.svg">
</p>

---

## 🚀 Features

- 📲 **Telegram Bot Commands**: `/buka`, `/tutup`, `/lampu_hijau`, `/lampu_merah`
- 🚪 **Motion Detection** with PIR for automatic gate opening
- 🔥 **Smoke/Gas Detection** using MQ2
- ⚡ **Current Monitoring** via INA219
- 🛂 **RFID Access Control** (RC522)
- 🚦 **Traffic Light Indicators** for gate status
- 💬 **Real-time Alerts** via Telegram
- 📊 **Optional PDF Reporting** for event logging *(upgradeable)*

---

## 🧰 Hardware Overview

| Component     | Description                     |
|---------------|---------------------------------|
| ESP32         | Main controller (WiFi capable)  |
| PIR Sensor    | Detects human motion            |
| MQ2 Sensor    | Detects smoke/gas               |
| INA219        | Measures current flow           |
| RC522 RFID    | (Optional) Card-based access    |
| Relay Module  | Opens/closes the gate           |
| Limit Switch  | Detects gate position           |
| LED (R/G)     | Gate open/close indicators      |
| Lampu Lalin   | Visual street light simulation  |

---

## 📷 System Preview

<p align="center">
  <img src="https://your-image-link.com/prototype.jpg" width="600" alt="SmartGate Prototype"/>
</p>

---

## 🛠️ Installation Guide

1. **Install Libraries** (Arduino IDE):
   - `WiFi`, `WiFiClientSecure`
   - `UniversalTelegramBot`
   - `SPI`, `MFRC522`
   - `MQ2`
   - `Adafruit INA219`

2. **Clone this repo:**

```bash
git clone https://github.com/yourusername/smartgate-esp32.git
