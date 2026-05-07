# 🚀 Sistem Kontrol Terpadu & Monitoring Lingkungan (Sispeng)
### **Politeknik Negeri Bandung - Teknik Refrigerasi dan Tata Udara**

![Status](https://img.shields.io/badge/Status-Development-yellow)
![Platform](https://img.shields.io/badge/Platform-ESP32-blue)
![IoT](https://img.shields.io/badge/IoT-Enabled-green)

Proyek ini merupakan sistem automasi berbasis **ESP32** yang dirancang untuk memantau parameter lingkungan (Suhu & Cahaya) serta mengontrol berbagai beban elektrik secara otomatis maupun manual. Data pemantauan disimpan secara offline ke dalam **SD Card** dan didokumentasikan secara online melalui **GitHub Pages**.

---

## 👥 Anggota Tim
Proyek ini dikembangkan oleh kelompok mahasiswa Polban:
* **Aldean Satrio** - *Lead Software & IoT Integrator*
* **Abdullah Faaiz Al Waafi** - *Hardware Specialist & Power Management*
* **Fatih Wibowo** - *AC Circuit & Safety Engineer*
* **Alviansyah** - *Mechanical Design & Sensor Calibration*

---

## 🛠️ Spesifikasi Perangkat
| Komponen | Deskripsi |
| :--- | :--- |
| **Microcontroller** | ESP32 DevKit V1 |
| **Sensor Suhu** | DHT22 (High Accuracy) |
| **Sensor Cahaya** | LDR (Light Dependent Resistor) |
| **Display** | LCD 16x2 with I2C Module |
| **Storage** | Micro SD Card Module (Data Logging) |
| **Relay** | 4-Channel 12V Module |
| **Beban DC** | Motor DC 12V, Kipas 12V & 5V |
| **Beban AC** | Lampu AC 10W & 12W |

---

## 📋 Fitur Utama
1. **Real-time Monitoring**: Menampilkan data suhu dan intensitas cahaya pada LCD 16x2.
2. **Data Logging**: Menyimpan log data sensor ke dalam file `.csv` di SD Card untuk analisis lebih lanjut.
3. **Smart Control**: 
   * Automasi kipas berdasarkan ambang batas suhu.
   * Kontrol lampu dan motor menggunakan relay.
4. **IoT Dashboard
