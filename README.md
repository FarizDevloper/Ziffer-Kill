# 🚪 SmartGate - Sistem Gerbang Otomatis Berbasis ESP32

![Smart Gate](https://www.example.com/gate_image.jpg)

**SmartGate** adalah sistem gerbang otomatis cerdas berbasis **ESP32**, dikendalikan melalui **Telegram Bot**, dilengkapi dengan **sensor gerak (PIR)**, **sensor asap (MQ2)**, **sensor arus**, **RFID**, serta **lampu lalu lintas** untuk indikasi gerbang. Sistem ini cocok digunakan untuk rumah pintar, garasi otomatis, atau sistem keamanan industri.

---

## ✨ Fitur Utama

- 🔐 **Kontrol Gerbang Otomatis** via Telegram (/buka, /tutup)
- 🛂 **Otentikasi RFID** dengan MFRC522
- 🚶 **Deteksi Gerakan** otomatis membuka gerbang
- 💨 **Deteksi Asap & Overcurrent** untuk keamanan
- 🚦 **Lampu Lalu Lintas Otomatis** (Merah & Hijau)
- 💬 **Notifikasi Telegram Real-time**
- 🔒 **Limit Switch** sebagai deteksi status buka/tutup gerbang
- 🔧 Kode open-source, bisa dikustomisasi sesuai kebutuhan

---

## ⚙️ Teknologi & Komponen

| Komponen            | Fungsi                            |
|---------------------|------------------------------------|
| ESP32               | Mikrokontroler utama               |
| MFRC522             | Pembaca kartu RFID                 |
| Sensor PIR          | Deteksi gerakan                    |
| Sensor MQ2          | Deteksi asap                       |
| INA219 / ADC        | Deteksi arus listrik               |
| Relay               | Kontrol gerbang otomatis           |
| Limit Switch        | Posisi gerbang (terbuka/tertutup) |
| LED & Lampu Lalin   | Indikasi status gerbang            |

---

## 🛠️ Instalasi

1. **Siapkan Library:**
   - WiFi
   - SPI
   - Wire
   - MFRC522
   - UniversalTelegramBot
   - WiFiClientSecure
   - ArduinoJson
   - MQ2
   - Adafruit INA219 *(opsional untuk arus)*

2. **Upload ke ESP32** dengan Arduino IDE atau PlatformIO

3. **Set Konfigurasi:**

```cpp
const char* ssid = "NAMA_WIFI";
const char* password = "PASSWORD_WIFI";
#define BOT_TOKEN "TOKEN_TELEGRAM_BOT";
#define CHAT_ID "CHAT_ID_TELEGRAM";
