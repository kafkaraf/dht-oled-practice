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
