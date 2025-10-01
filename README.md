# dht-oled-practice
Proyek latihan Arduino untuk membaca sensor DHT11 (suhu &amp; kelembapan) dan mengatur LED berdasarkan nilai yang dibaca.
Dengan menampilkan data ke OLED 0.96" atau menyalakan buzzer saat ambang tertentu tercapai.

**Tools yang digunakan :**
- ESP32 DevkitV1
- ESP32 Expansion Board (Gak Wajib)
- DHT11
- Display OLED 0.96 (Yellow)
- Breadboard + Jumper (Male to Female)

**Wiring & Pin :**

DHT11
- (+) : (hubungkan ke 5V atau 3.3V, tergantung board)
- (-) : GND
- Out : Pin D15
  
OLED Display
- VCC : 5V
- GND : GND
- SDA : A4
- SCL : A5

ESP32 DevkitV1 Datasheet :
<img width="4800" height="3360" alt="ESP32-DevkitV1 Datasheet" src="https://github.com/user-attachments/assets/7af2dd01-2940-460e-88f9-679f4771eb3e" />

Dokumentasi :
![DHT11-OLED](https://github.com/user-attachments/assets/818c63f6-c70a-42c0-85ac-2e37be1daa20)
