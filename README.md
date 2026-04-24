#  Robotivia Hackathon Competition Robot

 **Hackathon Robotics Project**  
 Developed by **SOUL Team**  
 Zagazig University & Partner Universities

---

##  Project Overview
This project presents a **fully integrated multi‑functional mobile robot** developed for the **Robotivia Hackathon 1.0** competition.  
The robot is designed to autonomously perform **Line Following**, **Obstacle Avoidance**, and **Pick & Place operations**, with an additional **Bluetooth‑based remote control mode**.

The system integrates **mechanical design, embedded electronics, and intelligent control algorithms** into a single modular robotic platform.

---

##  Problem Statement
Design and implement a competition‑ready robot capable of:
- Accurate autonomous navigation
- Real‑time obstacle detection and avoidance
- Object manipulation using a robotic arm
- Seamless switching between autonomous and manual modes
- Stable performance under high current and mechanical loads

---

##  System Architecture
The robot uses a **dual‑microcontroller architecture** to ensure stability and task separation:

- **Arduino 1** → Navigation Subsystem  
  - Line Following  
  - Obstacle Avoidance  

- **Arduino 2** → Manipulation & Communication  
  - Robotic Arm Control  
  - Bluetooth Remote Control  

This separation prevents interference between high‑current servo operations and navigation logic.

---

##  Key Features
- ✅ Autonomous Line Following using 5‑channel IR sensor array  
- ✅ Real‑time Obstacle Avoidance using Ultrasonic Sensor with Servo Scanning  
- ✅ 5‑DOF Robotic Arm (Pick & Place)  
- ✅ Bluetooth Remote Control via Mobile Application  
- ✅ Manual & Autonomous Mode Switching  
- ✅ Robust Power Management & Battery Monitoring  

---

##  Technologies & Components

### 🔌 Electronics
- Arduino Uno (Dual Controller System)
- L298N H‑Bridge Motor Driver
- HC‑05 Bluetooth Module
- 5‑Channel IR Sensor Array
- Ultrasonic Sensor (HC‑SR04)
- DC‑DC Buck Converters
- Battery Management System (BMS)

###  Actuators
- 4 × DC Motors (Differential Drive)
- 3 × SG‑90 Micro Servos
- 3 × MG‑996R High Torque Servos

###  Software
- Embedded C (Arduino)
- Finite State Machine for mode switching
- Threshold‑based control logic
- PWM‑based servo control
- MIT App Inventor (Mobile App)

---

## How It Works
1. **Line Following Mode**
   - IR sensors detect contrast
   - Motor speeds dynamically adjusted

2. **Obstacle Avoidance Mode**
   - Ultrasonic sensor scans environment
   - Robot stops, scans left/right, and reroutes

3. **Pick & Place**
   - 5‑DOF arm executes predefined motion sequences
   - Smooth PWM ramping ensures stability

4. **Remote Control**
   - Bluetooth commands override autonomous behavior safely

---

##  Testing & Validation
-  MATLAB‑based simulations (mechanical, electrical, control)
-  Indoor & outdoor field testing
-  Load testing for motors and servos
-  Thermal and power stability analysis
-  Iterative optimization cycles

---

##  Results
- Stable autonomous navigation
- Reliable obstacle avoidance
- Precise object manipulation
- Smooth mode transitions
- Robust performance under peak current loads

---

##  Achievements
- 🥇 **1st Place – Robotivia Hackathon Competition**
- Successfully demonstrated a fully functional competition‑grade robot

---

## 🔮 Future Improvements
- AI‑based vision system (camera + ML)
- Enhanced power efficiency
- Wi‑Fi connectivity
- Stronger lightweight chassis materials
- IMU integration for advanced navigation

---

## 👥 Team
**SOUL Team**
- **Moataz Rafik Hamdy** – Project Manager & Documentation &Electronics  
- **Omar Ayman Mohamed** – Software & Control Systems  
- **Adham Abd El‑Fattah** – Electronics & Hardware  
- **Hazem Abd El‑Fattah** – Mechanical Design & Testing  

---

⭐ If you find this project interesting, feel free to explore the repository and reach out!