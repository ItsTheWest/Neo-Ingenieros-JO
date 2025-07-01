<div align="center">
  
# Vehicle Documentation

### Development and construction of an autonomous vehicle for the World Robot Olympiad (WRO)
---
</div>

This document provides a detailed description of the development, construction, and validation of an autonomous vehicle designed to compete in the World Robot Olympiad (WRO). The main technical objective was to enable the robot to complete three laps on a closed circuit, accurately avoiding walls and intermediate obstacles.

Throughout the process, challenges were addressed in three key areas: mechanics, electronics, and intelligent control. Through multiple technical iterations, both the physical design and navigation algorithm were optimized, resulting in a robust, reliable system capable of meeting the competition's demanding requirements

---

## ✏️ Phase 1 – Concept Design and LEGO-Based Prototype

The initial phase focused on designing the robot based on dimensional sketches and functional concepts to ensure maneuverability and performance.

### 🧱 Physical Build

- A preliminary chassis was constructed using **LEGO pieces**, which allowed quick prototyping and a clear visual of the intended structure.
- Special attention was given to selecting **agile wheels**, aiming for smooth mobility and accurate turns.

### 🔌 Initial Electronics Setup

- **Microcontroller:** Arduino UNO  
- **Rear-Wheel Movement:** Driven by a DC motor  
- **Motor Controller:** L298N H-Bridge  
- **Power Supply:** Elegoo battery  
- **Arduino Adapter Board:** Used to simplify wiring and component connections  

This stage provided the robot with basic movement capabilities and established a foundation for future integration.

---

## ⚙️ Phase 2 – Sensor Integration and Functional Expansion

Once the robot could move independently, additional components were added to meet competition demands and allow environmental interaction.

### 🔍 Installed Modules

- **Ultrasonic Sensors (2x):** Used for obstacle detection in front and side directions  
- **Pixy2 Camera:** Enabled object or color tracking through visual input  
- **Servo Motor:** Allowed the robot to control the steering angle and change direction autonomously  

These upgrades allowed the robot to interpret its surroundings and make decisions based on sensor input, increasing its level of autonomy.

---

## 🛠️ Phase 3 – Hardware Reinforcement and Electrical Optimization

After testing, several issues were identified with the robot's structure and electrical system, leading to necessary improvements.

### 🧩 Mechanical Adjustments

- The **rear wheel system** built with LEGO was unstable. It was replaced with a **3D-printed gear mechanism**, enabling better torque transfer, improved rotation smoothness, and higher vehicle speed.

### ⚡ Power and Control Upgrades

- The **Elegoo battery** was replaced by **three 3.5V batteries connected in series**, offering increased voltage and more consistent power output.
- The **L298N motor driver** was swapped for an **HG7881 driver**, which consumed less voltage and required fewer GPIO pins on the microcontroller.

These changes greatly enhanced the robot’s mechanical stability, energy efficiency, and response time.

---

## 🚀 Phase 4 – Final Additions and Advanced Control

In the final development phase, the robot was equipped with advanced modules to increase precision and control capabilities.

### 🧠 New Features

- **Gyroscope:** Used to store the robot’s initial coordinates and return to the original position (self-parking logic)
- **Power Button:** Manually activates battery flow to the circuit
- **Breadboard:** Used to expand ground and voltage lines, improving wiring organization
- **Upgraded Front Steering:** Implemented using **3D-printed components**, increasing directional control and structural strength

---

## 🧠 Conclusion

The robot's development followed a structured, iterative approach. From simple sketches and LEGO prototyping to advanced sensor integration and 3D-printed enhancements, the vehicle evolved into a robust, efficient, and autonomous machine ready for competition. The final design prioritizes stability, power efficiency, and intelligent navigation.

---

## 📁 Suggested Repository Structure





