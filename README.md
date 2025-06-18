# AquaWaste Collector with IoT-Based Water Pollution Monitoring and Tracking System

## 🚀 Overview

This is my final year engineering project—a smart, semi-autonomous aquatic vehicle designed to collect waste from water bodies while simultaneously monitoring pollution levels in real time using IoT.

Built using Arduino, ESP8266, and multiple sensors, the system collects, analyzes, and transmits environmental data (such as pH, turbidity, temperature, humidity, and water levels) to ThingSpeak, enabling remote monitoring.

Additionally, the boat can be controlled manually via a Bluetooth module or NRF24L01 joystick-based controller.

---

## 🧠 Key Features

- 🛶 Autonomous Waste Collection using propeller-driven motors
- 🌐 IoT-based Monitoring (via ThingSpeak)
- 📊 Real-Time Parameters:  
  - pH of water  
  - Turbidity  
  - Temperature and Humidity (via DHT11)  
  - Water Level (Ultrasonic Sensor)
- 🎮 Remote Control Options:
  - Bluetooth App (HC-05 module)
  - NRF24L01 + Joystick Controller
- 🔋 Powered by 3.7V Batteries, 12V Motors, and regulated via Arduino Uno/Nano

---

## 🛠️ Technologies & Hardware Used

| Category | Components |
|---------|------------|
| Microcontrollers | Arduino Uno, Arduino Nano, ESP8266 |
| Sensors | pH Sensor, Turbidity Sensor, Ultrasonic Sensor, DHT11 |
| Communication | NRF24L01 Transmitter & Receiver, HC-05 Bluetooth Module |
| Others | L293D Motor Driver, 12V Motors, Joystick, Batteries, Propellers |

---

## 📂 Project Structure

├── Arduino_Codes/
│   ├── esp8266_data_sender.ino
│   ├── sensor_reader.ino
│   └── bluetooth_control.ino
├── PCB_Design/
│   ├── schematic.png
│   └── board_layout.png
├── NRF_Control/
│   ├── transmitter.ino
│   └── receiver.ino
├── README.md
└── Documentation/
    ├── Project_Report.pdf
    └── Literature_Survey.pdf

## 📜 How to Run
1. Upload Codes:
Use Arduino IDE to upload respective .ino files to:

ESP8266 for IoT

Arduino Uno/Nano for motor + sensor control

2. Connect Hardware:
Assemble the sensors and actuators as per your circuit diagram.

Ensure Wi-Fi credentials are correctly set in ESP8266 code.

3. View Data:
Open ThingSpeak to view real-time graphs.

4. Control the Boat:
Via Bluetooth App (like Serial Bluetooth Terminal)

OR use NRF-based joystick remote

## 🏁 Outcomes
✅ Successfully tested in local water bodies

✅ Received positive feedback from faculty during evaluation

✅ Demonstrated real-time water quality tracking with waste removal

## 🙌 Acknowledgements
Thanks to all mentors, lab staff, and teammates who supported this project. Special thanks to MAKAUT University for providing this opportunity.

## 📬 Contact
Mima Dhali
Final Year B.Tech ECE
Email - mimadhali2003@gmail.com



