# Sensors & Actuators – Mechatronics Lab

This page covers the basics of **sensors** and **actuators**, their role in mechatronic systems, and practical lab activities.

## Table of Contents
- [Introduction](#introduction)
- [Sensors](#sensors)
  - [Types of Sensors](#types-of-sensors)
- [Actuators](#actuators)
  - [Types of Actuators](#types-of-actuators)
- [System Example](#system-example)
- [Lab Activity](#lab-activity)
- [References](#references)

---

## Introduction
In mechatronics, **sensors** measure real-world variables and **actuators** perform actions based on control signals. Together, they form the foundation of any intelligent system.

---

## Sensors
Sensors convert **physical phenomena** into electrical signals.

### Types of Sensors
1. **Position Sensors** – Potentiometers, encoders.
2. **Proximity Sensors** – Infrared, ultrasonic.
3. **Environmental Sensors** – Temperature, humidity.
4. **Force & Pressure Sensors** – Load cells, barometric sensors.

---

## Actuators
Actuators convert **electrical signals** into physical movement or force.

### Types of Actuators
1. **Electric Motors** – DC, stepper, servo.
2. **Hydraulic Actuators** – High-force applications.
3. **Pneumatic Actuators** – Lightweight, quick action.
4. **Shape Memory Alloys** – For micro-actuation.

---

## System Example
![Sensor-Actuator Diagram](https://upload.wikimedia.org/wikipedia/commons/5/5e/Control_system_block_diagram.png "Basic Control System Diagram")  
*Figure 1: A simple closed-loop system where sensors feed information to a controller, which then drives an actuator.*

---

## Lab Activity
**Goal:** Create a temperature-controlled fan system.  

**Steps:**
1. Connect a **DHT11 temperature sensor** to an Arduino.
2. Read sensor values in real-time.
3. If temperature exceeds 30°C, activate a **DC motor fan**.
4. Display temperature and fan status on an LCD.

---

## References
- [Wikipedia – Sensors](https://en.wikipedia.org/wiki/Sensor)  
- [Wikipedia – Actuator](https://en.wikipedia.org/wiki/Actuator)  
- [Arduino – DHT11 Tutorial](https://randomnerdtutorials.com/arduino-dht11-dht22-temperature-humidity-sensor/)

---