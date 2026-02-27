# 🚆 Smart Railway Track Monitoring System

A real-time railway track defect detection system built using Arduino and Ultrasonic Sensor.

This project detects cracks or abnormal gaps in railway tracks and triggers an alert using LED and Buzzer to prevent accidents.

---

## 🔧 Components Used

- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Piezo Buzzer
- LED
- 220Ω Resistor
- Breadboard & Jumper Wires

---

## 🧠 Working Principle

The ultrasonic sensor continuously measures the distance between the sensor and the railway track surface.

If the measured distance exceeds a predefined threshold (20 cm), it indicates a potential crack or abnormal gap in the track.

When a defect is detected:
- 🔴 LED turns ON
- 🔊 Buzzer sounds an alert

---

## ⚙️ Pin Configuration

| Component | Arduino Pin |
|------------|------------|
| TRIG | 9 |
| ECHO | 10 |
| LED | 6 |
| Buzzer | 7 |

---

## 💻 Arduino Code

(Include the Arduino code file here)

---

## 🚀 Features

- Real-time defect detection
- Simple and low-cost design
- Expandable to IoT-based monitoring
- Can be integrated with GSM/GPS modules

---

## 🔮 Future Improvements

- Cloud-based monitoring
- Python-based data logging
- AI-based anomaly detection
- SMS alert system
- GPS location tracking

---

## 📌 Applications

- Railway safety systems
- Smart transportation infrastructure
- Industrial safety monitoring

---

## 👨‍💻 Author

Aditya Kumar Sharma  
Cybersecurity & Digital Forensics Student  
VIT Bhopal
