<p align="center">
  <img src="https://github.com/user-attachments/assets/c69411e1-2df9-4d94-be2d-ed5590c26fd8">
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

## 🧠 Pin Mapping

| Component           | ESP32 Pin     |
|---------------------|---------------|
| PIR Sensor          | GPIO 13       |
| MQ2 Sensor          | GPIO 36       |
| INA219 (I2C)        | GPIO 21 / 22  |
| Relay (Gate)        | GPIO 25       |
| RFID SS / RST       | GPIO 5 / 17   |
| LED Hijau / Merah   | GPIO 14 / 27  |
| Limit Switches      | GPIO 32 / 33  |
| Lampu Lalin         | GPIO 12 / 26  |

## 💬 Telegram Commands

| Command      | Function                          |
|--------------|-----------------------------------|
| /start       | Displays welcome text             |
| /buka        | Opens the gate                    |
| /tutup       | Closes the gate                   |
| /lampu_hijau | Turns on green light              |
| /lampu_merah | Turns on red light                |

## 🧩 Ideas for Expansion

- 🌐 Add a web-based control interface
- ☁️ Log activities to Firebase or Google Sheets
- 📄 Export gate logs as PDF reports
- 📡 Add GPS-based Telegram alert messages



## 🌟 Support This Project 🌟

If you find this project helpful and would like to support its ongoing development, you can make a donation! 💖 Your contribution will help us continue improving the project, add new features, and maintain its functionality for all users. Every little bit counts, and your support is deeply appreciated! 🙏

### How to Contribute 💸

You can donate through the following platforms:

[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue?style=for-the-badge&logo=paypal)](https://www.paypal.com/donate?hosted_button_id=YOUR_PAYPAL_LINK)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Donate-yellow?style=for-the-badge&logo=buymeacoffee)](https://www.buymeacoffee.com/YOUR_USERNAME)
[![Ko-Fi](https://img.shields.io/badge/Donate-Ko--Fi-blue?style=for-the-badge&logo=ko-fi)](https://ko-fi.com/YOUR_USERNAME)

Every donation, big or small, helps us continue to work on this project and bring it to the next level. 🚀 Thank you for your support! 💖

---

### Thank You to Our Amazing Donors 🌟

We appreciate everyone who supports this project in any way. Your generosity makes all the difference. Thank you for being a part of our community! 💪

If you want to contribute in other ways (like coding, bug fixes, or feature suggestions), feel free to check out our [Contributing Guide](CONTRIBUTING.md). 🚀

---

![Thank You](https://user-images.githubusercontent.com/74038190/212284094-e50ceae2-de86-4dd6-9f9c-a3ebcb3ede9e.gif)












