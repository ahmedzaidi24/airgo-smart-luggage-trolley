# AIRGO: Smart Automated Luggage Trolley for Airports

## Overview
This repository presents **AIRGO** – an innovative motor-powered trolley system engineered to enhance airport mobility, passenger assistance, and flight navigation using smart automation. Developed as part of the **ENGR6005 – New Product Development** unit at Curtin University, AIRGO addresses critical transit challenges through a combination of IoT, embedded systems, and intelligent design.

AIRGO assists travelers in transporting heavy luggage autonomously while also providing real-time navigation, flight data, and safety alerts via a GPS-enabled touchscreen system.

---

## 📌 Objectives
- Simplify heavy luggage movement with motor assistance
- Eliminate airport weighing queue delays via on-board load sensors
- Deliver live navigation to gates and services with built-in GPS mapping
- Enhance security using weight-locking sensors that detect tampering
- Improve passenger experience via real-time flight updates and multilingual UI

---

## 💡 Key Features
### 🔧 Mechanical & Control System:
- **Servo Motor & Push Buttons**: For forward, backward, and directional control
- **Microprocessor (Raspberry Pi)**: Core processing unit integrated with airport DB
- **Obstacle Detection**: Ultrasonic sensors and Pi Camera V1.3 to prevent collisions

### ⚖️ Security & Load Management:
- **Load Sensor**: Measures luggage weight dynamically
- **Weight-Locking Feature**: Sounds an alarm upon unauthorized access

### 📲 Smart Display Interface:
- **Touchscreen UI**: Provides real-time flight data and navigation maps
- **GPS Integration**: Guides to terminal gates, food courts, lounges, etc.
- **Language Options**: Supports international users with multilingual UX

---

## 🧩 Product Architecture
The system integrates electromechanical components, Raspberry Pi modules, and sensory interfaces into a portable airport trolley.

```
[Push Buttons] ---> [Servo Motors] ---> [Wheels]
       |                  |
       v                  v
[Ultrasonic Sensors]   [Raspberry Pi]
       |                  |
[Pi Camera]         [Touchscreen GPS UI]
       |
[Load Sensor & Alarm]
```

---

## 🏗️ Prototyping Roadmap
| Stage                | Goal                                                                 |
|---------------------|----------------------------------------------------------------------|
| Proof of Concept    | Test core obstacle detection and servo motion via basic rig setup   |
| Functional Build     | Integrate all modules (Pi, sensors, UI) in a working form factor     |
| Low-Volume Units     | Fabricate small batch for pilot trials in select airports            |

---

## 🧱 Business Structure
### Company: **AIRGO Innovations Pty Ltd**
**Vision**: To lead global airport mobility solutions with intelligent automation.  
**Mission**: Deliver secure, smart, and energy-efficient trolleys to streamline passenger experiences.

### Revenue Streams:
- Direct B2B sales to airports and airlines
- Ad revenue from digital screen placements (retail & food outlets)
- Subscription model for software, analytics, and updates

---

## 🛠️ Tools & Technologies
- Raspberry Pi
- Python (Microcontroller logic)
- IoT Sensors (Ultrasonic, Load)
- Smart Display & UI Design (Touchscreen Tablet)
- CAD Sketches (for mechanical framework)

---

## 📁 Repository Structure
| File/Folder | Description |
|-------------|-------------|
| `Product_Plan.pdf` | Detailed description of AIRGO’s features, architecture, and prototype roadmap |
| `Business_Model.pdf` | Structure of AIRGO Innovations, revenue strategy, and logistics planning |
| `Marketing_Strategy.pdf` | Launch strategy, TAM/SAM/SOM estimates, pricing and success metrics |
| `Customer_Research.pdf` | Interview findings, insights, and lean canvas updates |
| `Sketches/` | Conceptual diagrams and architecture drawings |

---

## 👤 Author
**Syed Muhammad Ahmed Zaidi**  
Curtin University | Student ID: 20972008  
Unit: ENGR6005 – New Product Development

---

## 📄 License
For academic purposes only. Commercial use requires explicit permission from the author.

---

## 🚀 Status
📦 Currently at concept/prototype stage. Seeking collaboration for prototyping and testing in smart airport environments.
