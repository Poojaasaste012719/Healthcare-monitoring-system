# Healthcare-monitoring-system
Healthcare Monitoring System – Non-Contact Temperature &amp; Pulse Detection  This project is a Non-Contact Healthcare Monitoring System using Arduino Uno, designed to monitor patients’ body temperature and pulse rate in real-time.

# Healthcare Monitoring System

## Project Overview
This project is a **Non-Contact Healthcare Monitoring System** designed using **Arduino Uno**.  
It measures **temperature** and **pulse rate** of a person without direct contact and sends **real-time health data to the cloud**, allowing doctors to monitor patients remotely.

---

## Features
- Non-contact temperature measurement using an infrared temperature sensor (e.g., MLX90614)
- Pulse detection using a pulse sensor (e.g., Pulse Sensor AMPED)
- Real-time cloud integration to send data directly to doctors
- Data visualization via cloud dashboard (e.g., ThingSpeak, Firebase, or Adafruit IO)
- Alerts for abnormal readings

---

## Hardware Requirements
- Arduino Uno
- MLX90614 Infrared Temperature Sensor
- Pulse Sensor AMPED
- ESP8266 WiFi Module (for cloud connectivity)
- Breadboard & Jumper wires
- Power supply (5V)

---

## Software Requirements
- Arduino IDE
- Libraries:
  - `Wire.h` (for I2C sensors)
  - `Adafruit_MLX90614.h` (for temperature sensor)
  - `PulseSensorPlayground.h` (for pulse sensor)
  - `ESP8266WiFi.h` (for cloud connection)
  - `ThingSpeak.h` (or another cloud library)

---

## Project Setup
1. Connect sensors to Arduino Uno according to the circuit diagram in `Circuit_Diagram/CircuitDiagram.png`.
2. Open `Arduino_Code/Healthcare_Monitoring.ino` in Arduino IDE.
3. Update your WiFi credentials and cloud API key.
4. Upload the code to Arduino Uno.
5. Check your cloud dashboard for real-time health data.

---

## Usage
- Place the user’s finger on the pulse sensor and maintain a distance of 2–5 cm for temperature measurement.
- Data will automatically update in the cloud in real-time.
- Doctors or caregivers can monitor patient health remotely via the cloud dashboard.


## License
This project is licensed under the MIT License. See `LICENSE` for details.
