# 孵化器 Cyber-Inkubator IoT ESP32

Sistem monitoring inkubator berbasis IoT dengan tema **Cyberpunk UI**. Proyek ini menggunakan ESP32 untuk mengontrol lingkungan inkubator secara otomatis.

## 🚀 Fitur
- **Dashboard Cyberpunk**: UI Futuristik menggunakan CSS neon.
- **Real-time Chart**: Grafik suhu menggunakan Chart.js.
- **Auto-Spin Relay**: Motor berputar otomatis berdasarkan interval yang bisa diatur lewat Web.
- **Dual Channel Control**: Kontrol Kipas (Channel 2) dan Motor (Channel 1).
- **Monitoring LDR & DHT22**: Pantau cahaya dan suhu secara real-time.

## 🛠️ Komponen
- ESP32 DevKit V1
- Sensor DHT22 (Suhu & Kelembapan)
- Sensor LDR (Cahaya)
- Relay 4 Channel (Menggunakan 2 Channel)
- Motor DC & Kipas DC
- Step Down LM2596 (12V to 5V)

## 📌 Pinout
| Komponen | Pin ESP32 |
|----------|-----------|
| DHT22    | GPIO 4    |
| LDR      | GPIO 34   |
| Relay 1 (Motor) | GPIO 26 |
| Relay 2 (Kipas) | GPIO 27 |

## ⚙️ Cara Pakai
1. Masukkan library `SimpleDHT` di Arduino IDE.
2. Ganti SSID & Password WiFi.
3. Upload kode dan buka IP ESP32 di browser.
