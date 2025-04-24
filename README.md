# 🚨 Smart Security Gate System with Telegram Integration

![Smart Gate System](https://www.example.com/your_image.jpg)

Sistem keamanan otomatis berbasis **ESP32** yang mampu membuka dan menutup pintu menggunakan **sensor gerak**, **sensor asap**, **sensor arus**, dan **RFID**. Seluruh sistem terhubung dengan **Telegram Bot**, memungkinkan kontrol **jarak jauh secara real-time** melalui perintah sederhana seperti membuka pintu atau mengatur lampu lalu lintas.

---

## ✨ Fitur Unggulan

- ✅ Deteksi gerakan (PIR)
- 🚬 Deteksi asap (MQ2)
- ⚡ Deteksi arus berlebih
- 🪪 Akses kontrol dengan RFID
- 🔁 Kontrol relay otomatis
- 🚦 Lampu lalu lintas merah & hijau
- 💬 Kontrol dari Telegram: `/buka`, `/tutup`, `/lampu_hijau`, `/lampu_merah`
- 🔐 Keamanan pintu menggunakan limit switch
- 📡 Terhubung ke internet via WiFi

---

## 🔧 Hardware yang Dibutuhkan

- ESP32 Dev Board
- Sensor PIR
- Sensor MQ2
- Sensor Arus (ACS712 / INA219)
- RFID RC522
- Relay 1 Channel
- LED (Merah & Hijau)
- Limit Switch (x2)
- Breadboard + Kabel Jumper

---

## 🚀 Cara Instalasi

1. Clone repository ini:
   ```bash
   git clone https://github.com/username/smart-gate-system.git
   
Buka file .ino di Arduino IDE

Masukkan informasi berikut:

SSID & Password WiFi

Bot Token & Chat ID Telegram

Upload ke board ESP32 kamu

Monitor via Serial Monitor (115200)

---

📱 Perintah Telegram

Perintah	Fungsi
/buka	Membuka pintu secara otomatis
/tutup	Menutup pintu otomatis
/lampu_hijau	Menyalakan lampu hijau
/lampu_merah	Menyalakan lampu merah
