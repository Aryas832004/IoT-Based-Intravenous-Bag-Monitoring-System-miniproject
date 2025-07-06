# 💡 IoT-Based IV Bag Monitoring System

> A smart healthcare project that automates IV fluid level tracking using IoT and sensors — reducing human error and enabling real-time alerts for medical staff.

🎤 **Presented at International Conference on Advancement in Science, Engineering & Technology – 2025**  
📚 **Soon to be Published in International Conference Proceedings**

---

## 🧾 Abstract

Intravenous therapy is widely used in medical care but still lacks real-time monitoring. This project leverages **ESP8266**, **Load Cell**, and **Blynk App** to automate IV fluid level detection, notify staff wirelessly, and display status locally — ensuring **patient safety and efficient care**.

---

## ⚙️ System Overview

- **Microcontroller:** ESP8266 NodeMCU
- **Sensor:** 10kg Load Cell + HX711 Amplifier
- **Display:** 16x2 LCD via PCF8574 I2C
- **Notification:** Blynk App & LED alert
- **Software:** Arduino IDE + Blynk IoT Platform
- **Power Supply:** 5V DC

---

## 📈 Block Diagram

![Block Diagram](Images/block_diagram.png)

---

## 🔄 Flowchart

![Flowchart](Images/flowchart.png)

---

## 🧪 Circuit Diagram

![Circuit Diagram](Images/circuit_diagram.jpg)

---

## 📲 Output Screens & Setup

| Setup Top View | Setup Side View | Mobile Notification |
|----------------|------------------|----------------------|
| ![](Images/setup_photo_1.jpg) | ![](Images/setup_photo_2.jpg) | ![](Images/mobile_notification.jpg) |

---

## 💻 How It Works

1. **Weight Detection:** Load cell senses IV bag weight.
2. **Signal Amplification:** HX711 amplifies the signal and sends it to ESP8266.
3. **Data Processing:** ESP8266 calculates fluid weight.
4. **Display:** Current weight shown on 16x2 LCD.
5. **Threshold Alert:** If weight is low:
   - 🔴 LED turns ON
   - 📲 Blynk app sends notification
6. **Real-time Monitoring:** Enables medical staff to act quickly even remotely.

---

## 📂 File Structure

```
IOT_IV_Bag_Monitoring_System_Project/
├── Code/
│   └── main.ino
├── Images/
│   ├── block_diagram.png
│   ├── circuit_diagram.jpg
│   ├── flowchart.png
│   ├── setup_photo_1.jpg
│   ├── setup_photo_2.jpg
│   └── mobile_notification.jpg
├── Report/
│   └── ARYAreport.pdf
├── ConferencePaper/
│   └── conference_paper.doc
└── README.md
```

---

## 👨‍💻 Team Members

| Name         | Role           | Email |
|--------------|----------------|-------------------------------|
| Arya Sasikumar | Project Lead    | aryasasikumar2004@gmail.com  |
| Ajmal T A      | Developer       | ajmalzayan18@gmail.com        |
| Mahitha M      | Developer       | mahithamurali431@gmail.com    |
| Gowthami S     | Testing & Docs  | gowthami.s@ahalia.ac.in       |

### 👩‍🏫 Guide
- **Ms. Swetha C**, Dept. of ECE – swetha@ahalia.ac.in

---

## 🛠️ Setup Instructions

1. Wire the components as shown in `circuit_diagram.jpg`
2. Open `main.ino` in Arduino IDE
3. Install libraries: `HX711`, `Blynk`, `ESP8266WiFi`
4. Add Wi-Fi and Blynk credentials
5. Upload code to NodeMCU
6. Monitor IV bag status on:
   - LCD display
   - Mobile Blynk app

---

## 🚀 Future Enhancements

- Cloud analytics and IV usage prediction
- Central dashboard for multi-bed monitoring
- Auto shut-off valve integration
- Battery powered unit with wireless charging

---

## 📄 License

🔒 This project is for academic demonstration only. Contact the authors for reuse or research collaboration.

---
