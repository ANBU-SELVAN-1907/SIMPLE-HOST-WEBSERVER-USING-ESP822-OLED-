
# SIMPLE-HOST-WEBSERVER-USING-ESP8266-OLED-
This project uses an ESP8266 (NodeMCU) to create a simple web server that can be accessed from any browser on the same Wi-Fi network. A 1.96-inch OLED display is used to show the server status and IP address once the server is successfully started. This allows real-time visual feedback on the device itself.

---------------------------------------------------------------ANBU SELVAN -------------------------------------------------------------------------------------------

# 🌐 ESP8266 Web Server with 1.96" OLED Display

This project demonstrates how to create a simple web server using the **ESP8266 (NodeMCU)**. A **1.96-inch OLED display** is used to show whether the server has started successfully and display the IP address assigned to the ESP8266. This provides instant on-device feedback.

---

## 📦 Features

- Creates a web server using ESP8266.
- Displays "Server Started" and the IP address on a 1.96" OLED.
- Users can access a simple webpage hosted on the ESP8266.

---

## 🛠️ Hardware Required

- NodeMCU ESP8266 board  
- 1.96" OLED Display (I2C-based, SSD1306 or SH1106)  
- USB cable  
- Jumper wires  
- Breadboard (optional)

---

## 🔌 Circuit Connections

| OLED Pin | ESP8266 Pin |
|----------|-------------|
| VCC      | 3.3V        |
| GND      | GND         |
| SDA      | D2 (GPIO4)  |
| SCL      | D1 (GPIO5)  |

> ⚠️ Make sure the OLED module supports 3.3V logic levels.

---

## 🔧 Required Libraries

Install these libraries in the Arduino IDE via the Library Manager:

- `ESP8266WiFi`
- `Adafruit GFX Library`
- `Adafruit SSD1306` *(or `U8g2` for SH1106)*
- `Wire`


![image](https://github.com/user-attachments/assets/d65be681-967f-4d31-96a9-19328d0bbc91)

---

## 📄 What It Does

1. Connects to your Wi-Fi network.
2. Starts a local web server on port 80.
3. Displays “Server Started” and the IP address on the OLED screen.
4. Hosts a webpage that shows a custom message in the browser.

---

## 🌐 Web Server Output

When accessed in a browser:
![Screenshot 2025-06-15 150539](https://github.com/user-attachments/assets/127890e4-8a3e-4f71-a737-0e55e21f8aef)

