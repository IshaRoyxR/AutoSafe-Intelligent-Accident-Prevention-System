# 🚗 AutoSafe: Intelligent Accident Prevention System

## 📌 Overview
AutoSafe is an Arduino-based intelligent accident prevention system designed to improve vehicle safety using real-time obstacle detection and automatic braking.

The system continuously monitors the distance between the vehicle and nearby obstacles using an ultrasonic sensor. Based on the detected distance, the vehicle automatically adjusts its speed or stops completely to avoid collisions.

This project demonstrates the practical implementation of embedded systems, automation, and sensor-based control in smart vehicle safety applications.

---

## 🎯 Objectives
- Detect obstacles in real time
- Reduce vehicle speed automatically
- Prevent collisions using automatic braking
- Develop a low-cost intelligent safety prototype
- Simulate modern ADAS (Advanced Driver Assistance System) concepts

---

## ⚙️ Technologies & Components Used

### Hardware
- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- L293D Motor Driver
- DC Gear Motors
- Chassis
- Wheels
- Battery
- Connecting Wires

### Software
- Arduino IDE
- Embedded C / Arduino Programming

---

## 🧠 Working Principle

The ultrasonic sensor continuously measures the distance between the vehicle and obstacles ahead.

### Logic Used

| Distance from Obstacle | Vehicle Action |
|------------------------|----------------|
| Greater than 5m        | Normal Speed   |
| Between 2m and 5m      | Reduced Speed  |
| Less than or equal to 2m | STOP |

The Arduino UNO processes sensor data and sends control signals to the motor driver to adjust motor speed accordingly.

---

## 🔄 System Workflow

1. Ultrasonic sensor detects obstacle distance
2. Arduino processes distance data
3. Motor driver receives control signals
4. Vehicle speed is adjusted automatically
5. Vehicle stops if obstacle is too close

---

## 🔌 Circuit Diagram

(Add your circuit diagram image here)

Example:

```markdown
![Circuit Diagram](images/circuit_diagram.png)
```

---

## 🚘 Prototype Model

(Add prototype image here)

Example:

```markdown
![Prototype](images/prototype.jpg)
```

---

## 📂 Project Structure

```text
AutoSafe-Intelligent-Accident-Prevention-System/
│
├── README.md
├── AutoSafe_Presentation.pdf
├── code/
│   └── autosafe.ino
├── images/
│   ├── prototype.jpg
│   └── circuit_diagram.png
└── docs/
    └── report.pdf
```

---

## 🚀 Features
- Real-time obstacle detection
- Automatic braking mechanism
- Distance-based speed control
- Low-cost implementation
- Embedded systems application
- Educational and research-oriented prototype

---

## 📈 Future Enhancements
- Full collision avoidance system
- AI-based object detection
- Real vehicle integration
- Smart steering control
- IoT monitoring system
- EV safety integration
- Advanced Driver Assistance System (ADAS)

---

## 📚 Applications
- Smart vehicle safety systems
- Autonomous robotics
- Educational embedded projects
- Accident prevention systems
- Low-cost automation solutions

---

## 👨‍💻 Team Members
- Debanjan Biswas
- Arghyapratim Saha
- Sampath
- Sounak Chattapadhyay
- Satish Gupta
- Isha Roy
- Krish Shaw

---

## 🏫 Institution
**National Institute of Technology Agartala**

---

## 📄 Project Presentation
[View Project Presentation](./AutoSafe_Presentation.pdf)

---

## 🌟 Conclusion
AutoSafe demonstrates how embedded systems and automation can be used to improve vehicle safety through intelligent obstacle detection and automatic braking. The project successfully showcases a practical and affordable implementation of a smart safety mechanism suitable for educational, research, and future automotive applications.

---

## 📬 Contact
For collaboration or project discussion:

**Isha Roy**  
Electrical Engineering  
NIT Agartala
