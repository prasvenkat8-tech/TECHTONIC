# Sentinel – AI Predictive Safety Platform

Prevent incidents before they happen.

---

# Team Details

**Team Name:** Techtonic

**Institution:** SRM Institute of Science and Technology (SRMIST), Ramapuram

| S.No | Name | Role |
|------|-----------------------|--------------|
| 1 | Prasanna Venkatesh R | Team Leader |
| 2 | Kiran U | Team Member |
| 3 | Eswar Krishna R | Team Member |
| 4 | Tilak A L | Team Member |
| 5 | Sanjay R | Team Member |
| 6 | Syed Ammaar Ahmed | Team Member |

---

# Project Title

Sentinel – AI Predictive Safety Platform

Tagline: Prevent incidents before they happen.

---

# Problem Statement

Traditional safety systems mainly detect incidents after they occur. Most systems rely on individual sensors or CCTV footage without understanding the complete situation, resulting in delayed responses and limited decision-making.

---

# Proposed Solution

Sentinel is an AI-powered predictive safety platform that combines multiple IoT sensors with artificial intelligence to understand safety events in real time.

Instead of simply detecting motion, Sentinel analyzes sensor data, verifies authorized users using RFID, captures images, explains the detected event using AI, logs every activity, and recommends the appropriate action before incidents become critical.

---

# Features

- Motion Detection
- RFID-Based User Authentication
- Distance Measurement
- Image Capture using ESP32-CAM
- Temperature Monitoring
- AI-Based Event Analysis
- Intelligent Safety Recommendations
- Event Logging
- Real-Time Alerts using Buzzer and LED

---

# Complete Tech Stack

## Hardware
- ESP32
- ESP32-CAM
- Ultrasonic Sensor
- RFID RC522 Module
- RFID Cards
- Temperature Sensor
- Buzzer
- LED
- Breadboard
- Jumper Wires

## Software
- Python
- Arduino IDE
- Visual Studio Code
- Git
- GitHub

## Libraries
- OpenCV
- PySerial
- Flask
- Pandas

## AI
- Gemini API / OpenAI API (Final API will be selected during development)

---

# System Architecture

<img width="1536" height="1024" alt="WhatsApp Image 2026-07-24 at 12 50 01 (1)" src="https://github.com/user-attachments/assets/109040bd-2a27-4c3d-83d9-ce19e250832d" />

Flow:

Sensors

↓

ESP32

↓

Python Application

↓

AI Analysis Engine

↓

Decision Engine

↓

Dashboard + Alerts + Event Logs

---

# Detailed Workflow

1. User approaches the system.
2. Ultrasonic sensor detects movement.
3. RFID module verifies whether the user is authorized.
4. Temperature sensor records environmental conditions.
5. ESP32-CAM captures an image.
6. Sensor data and image are sent to the AI engine.
7. AI analyzes the complete situation.
8. AI generates an explanation of the detected event.
9. The system recommends the appropriate safety action.
10. The event is logged.
11. LED and buzzer provide visual and audio alerts.

---

# Folder Structure

```
Sentinel/
│
├── README.md
├── app.py
├── hardware/
├── sensors/
├── ai/
├── dashboard/
├── images/
├── logs/
├── requirements.txt
└── docs/
```

---

# Installation Guide

1. Clone the repository.

```
git clone <repository-url>
```

2. Open the project in Visual Studio Code.

3. Install the required Python packages.

```
pip install -r requirements.txt
```

4. Upload the ESP32 code using Arduino IDE.

5. Connect all hardware components.

6. Run the Python application.

```
python app.py
```

---

# Usage Guide

1. Power on the ESP32.
2. Launch the Python application.
3. Present an RFID card.
4. Move near the sensing area.
5. Observe the AI analysis.
6. View recommendations.
7. Monitor alerts and event logs.

---

# API / Database Documentation

## AI API

Gemini API / OpenAI API (To be finalized)

## Database

Initially, event logs will be stored locally.

Future versions may integrate:
- Firebase
- MongoDB
- MySQL

---

# AI Workflow

Sensor Data

+

Captured Image

↓

AI Processing

↓

Context Analysis

↓

Event Explanation

↓

Safety Recommendation

↓

Event Logging

---

# Hardware Components

| Component | Quantity |
|------------|----------|
| ESP32 | 1 |
| ESP32-CAM | 1 |
| Ultrasonic Sensor | 1 |
| RFID RC522 | 1 |
| RFID Cards | 1|
| Temperature Sensor | 1 |
| Buzzer | 1 |
| LED | 2 |
| Breadboard | 1 |
| Jumper Wires | As Required |

<img width="1402" height="1122" alt="ChatGPT Image Jul 24, 2026, 01_54_13 PM" src="https://github.com/user-attachments/assets/f846ea22-564c-49a1-ada1-b06ece4464d9" />




---

# Security Measures

- RFID-Based Access Verification
- Sensor Data Validation
- Secure Event Logging
- AI-Based Decision Verification
- Controlled Alert Generation

---

# Testing and Performance

Modules Tested

- Motion Detection
- RFID Authentication
- Distance Measurement
- Camera Module
- Temperature Monitoring
- AI Analysis
- Alert System
- Event Logging

Performance metrics will be added after implementation and testing.

---

# Challenges Faced

- Integrating multiple sensors
- Hardware calibration
- Real-time communication between ESP32 and Python
- AI response optimization
- Sensor synchronization

---

# Future Scope

- Face Recognition
- Fire Detection
- Smoke Detection
- Cloud Dashboard
- Mobile Application
- SMS and Email Alerts
- Predictive Analytics
- Multi-location Monitoring

---

# Demo

## Project Screenshots






---

# References

- ESP32 Documentation
- ESP32-CAM Documentation
- Arduino Documentation
- Python Documentation
- OpenCV Documentation
- Gemini API Documentation / OpenAI API Documentation
