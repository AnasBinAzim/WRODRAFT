<div align="center">
  <img src="https://github.com/user-attachments/assets/172c3a2a-33b5-4c01-a7e5-fbb2edcce263" alt="Mayerdoa Robotics Logo" width="200" />
</div>

# 🤖 WRO Bot Project

Welcome to the World Robot Olympiad (WRO) Bot project repository! This bot is designed to perform efficiently in the WRO competition, leveraging a combination of LEGO Technic parts, a Raspberry Pi, various sensors, and custom components. This document provides an overview of the bot’s assembly, functionality, and usage instructions.

---

## 📜 Table of Contents
- [Introduction](#introduction)
- [Project Objective](#project-objective)
- [Team Members](#team-members)
- [Features](#features)
- [Hardware Components](#hardware-components)
- [Assembly Instructions](#assembly-instructions)
  - [Chassis Structure](#chassis-structure)
  - [Drive System](#drive-system)
  - [Electronics and Power System](#electronics-and-power-system)
  - [Sensors](#sensors)
  - [Mounting the Raspberry Pi and Camera](#mounting-the-raspberry-pi-and-camera)
- [Software Setup](#software-setup)
- [Code Overview](#code-overview)
- [Usage](#usage)
- [Troubleshooting](#troubleshooting)
- [Gallery](#gallery)
- [Future Improvements](#future-improvements)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## 🎉 Introduction

The **WRO Bot Project** is dedicated to building a highly capable, autonomous robot designed to excel in the **World Robot Olympiad (WRO) 2024 Future Engineers** category. With the theme of **smart and sustainable mobility**, this bot will perform intricate tasks under a range of challenging conditions. We are using advanced robotics principles, a robust **Raspberry Pi** processing system, modular **LEGO Technic** components for easy and adaptable assembly, and a suite of sensors to help the robot navigate and interact with the environment. Our goal is to create a bot that demonstrates **precision, efficiency, and adaptability** across various mission scenarios.

---

## 🎯 Project Objective

This project aims to create a competitive and reliable robot that can autonomously execute tasks in a time-sensitive, dynamic environment as outlined in the **WRO Future Engineers** competition. Key objectives include:

1. **Build a High-Performance Robot**  
   Design a robust robot that can withstand intensive tasks in WRO’s mission-based rounds, focusing on modularity to adapt to different configurations and scenarios. The bot should be capable of precise movement and efficient task execution, including object manipulation, autonomous pathfinding, and obstacle navigation.

2. **Utilize Modular and Reusable Parts**  
   By incorporating LEGO Technic components and custom 3D-printed mounts, the bot’s structure is both modular and reusable, allowing for quick reconfiguration and minimal downtime. This modularity enables easy assembly, repair, and adaptations as needed, ensuring optimal performance across different WRO rounds and mission variations.

3. **Implement Advanced Control Code**  
   Develop sophisticated algorithms and control code to manage sensor data interpretation, path planning, and task handling. The code is designed to enable the robot to make autonomous decisions in real-time, adapting to obstacles, detecting objects, and completing missions according to WRO specifications. This includes efficient data handling from ultrasonic, infrared, and camera sensors to ensure smooth and precise task completion under varying conditions.

4. **Optimize for Future Engineers Rounds**  
   Prepare the robot specifically for the missions of the Future Engineers category, which often requires complex maneuvers like object sorting, transport, alignment, and advanced navigation. The bot should be prepared to handle tasks that may change each round, ensuring a flexible yet powerful framework for meeting each mission’s demands.

---

This setup will help **Team MAYERDOA_ROBOTICS** achieve excellence in WRO’s challenging rounds, bringing together innovative robotics principles and real-world engineering solutions.

---

## 👥 Team Members

- **Anas Bin Azim** – [anas.azim.71@gmail.com](mailto:anas.azim.71@gmail.com)
- **Rakibul Islam** – [rakibul.rir06@gmail.com](mailto:rakibul.rir06@gmail.com)
- **Mohiuddin Sami** – [sm.mohiuddin.sami@gmail.com](mailto:sm.mohiuddin.sami@gmail.com)

**Team**: **MAYERDOA_ROBOTICS**  
**Country**: **Bangladesh**  
**Event**: **2024 WRO National Final (Future Engineers)**

---

## 🚀 Features

- **LEGO Technic-based Chassis**: Modular, durable, and easy to assemble.
- **Raspberry Pi Controller**: Provides processing power for sensor integration and control logic.
- **Sensor Array**: Ultrasonic, infrared, and other sensors for obstacle detection, line tracking, and environmental interaction.
- **Custom 3D-Printed Mounts**: Holds components securely in place.
- **Efficient Power System**: Ensures smooth and sustained operation during tasks.

---

## 🧩 Hardware Components

- **Raspberry Pi 4**: The brain of the bot, handling computations and sensor data.
- **LEGO Technic Parts**: For the primary structure and chassis of the bot.
- **Ultrasonic Sensors**: Used for distance measurement and obstacle detection.
- **Infrared Sensors**: Helps in line tracking and navigation.
- **DC Motors**: Provides propulsion to drive the wheels.
- **3D Printed Parts**: Custom mounts and holders for precise component placement.
- **Power Supply**: Batteries and regulators to power all components.

---

## 🔧 Assembly Instructions

### 🏗️ Chassis Structure

The bot's main frame is built using LEGO Technic parts, providing a sturdy base for mounting all other components.

![Chassis Assembly](./images/01_chassis_structure.jpg)

*Additional Photos*:
- ![Chassis Detail](./images/02_chassis_detail.jpg)
- ![Frame Assembly](./images/03_frame_assembly.jpg)

### 🚗 Drive System

The drive system consists of DC motors connected to the wheels, providing the necessary propulsion and control for movement.

![Drive System](./images/04_drive_system.jpg)

*Additional Photos*:
- ![Motor Detail](./images/05_motor_detail.jpg)
- ![Wheel Assembly](./images/06_wheel_assembly.jpg)

### ⚡ Electronics and Power System

- **Power Module**: Supplies consistent power to the Raspberry Pi and motors.
- **Wiring**: Organized to ensure reliable connectivity and reduce interference.

![Electronics Setup](./images/07_electronics_setup.jpg)

*Additional Photos*:
- ![Power Supply](./images/08_power_supply.jpg)
- ![Battery Connection](./images/09_battery_connection.jpg)

### 🔍 Sensors

Various sensors are strategically placed to provide the bot with spatial awareness, enabling obstacle avoidance, line tracking, and environmental data collection.

![Sensors Array](./images/10_sensors_array.jpg)

*Additional Photos*:
- ![Ultrasonic Sensor Placement](./images/11_ultrasonic_sensor.jpg)
- ![Infrared Sensor Setup](./images/12_infrared_sensor.jpg)

### 📸 Mounting the Raspberry Pi and Camera

The Raspberry Pi is securely mounted on the bot using custom 3D-printed parts, which also provide ventilation. The camera is positioned for optimal visibility and angle.

![Raspberry Pi and Camera Mount](./images/13_raspberry_camera.jpg)

*Additional Photos*:
- ![Camera Detail](./images/14_camera_detail.jpg)
- ![Processor Mount](./images/15_processor_mount.jpg)

---

## 💻 Software Setup

1. **Install Dependencies**:
   ```bash
   sudo apt update
   sudo apt install python3 python3-pip
   pip3 install -r requirements.txt




---

### Thank you for following our journey! We hope SMOKI inspires you to dream big and engineer even bigger! 💖🚀
