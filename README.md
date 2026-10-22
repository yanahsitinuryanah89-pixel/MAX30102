# Dokumentasi Sensor MAX30102

Proyek ini berisi program dasar untuk membaca detak jantung dan saturasi oksigen darah menggunakan microcontroller berbasis Arduino.

## 🛠️ Skema Perkabelan (Wiring Diagram)

Hubungkan pin sensor MAX30102 ke papan Arduino Anda sesuai dengan tabel panduan berikut:

| Pin Sensor MAX30102 | Pin Papan Arduino Uno / Nano | Fungsi |
| :--- | :--- | :--- |
| **VCC** | 3.3V / 5V | Jalur Daya Utama |
| **GND** | GND | Jalur Grounding |
| **SCL** | A5 (atau Pin SCL khusus) | Jalur Clock I2C |
| **SDA** | A4 (atau Pin SDA khusus) | Jalur Data I2C |

## 🚀 Cara Penggunaan
1. Buka berkas `MAX30102.ino` di Arduino IDE Anda.
2. Pastikan Anda sudah menginstal pustaka (library) **SparkFun MAX30105**.
3. Unggah (upload) kode ke papan Arduino Anda.
4. Buka **Serial Monitor** pada baudrate 115200 untuk melihat hasil pembacaan sensor.
5.
