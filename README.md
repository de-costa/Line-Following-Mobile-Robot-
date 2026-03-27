# 🤖🛤️ Integrated Line-Following Mobile Robot with Obstacle Avoidance and Color-Based Pick-and-Place

## ✦ Overview

This project presents the design and development of an autonomous mobile robot capable of performing multiple robotic tasks in a predefined sequence. The robot is designed to follow a line, detect and avoid obstacles, identify a target object based on color, pick it up using a servo-based mechanism, and place it at a designated destination. The system demonstrates the practical integration of sensing, control logic, embedded programming, and actuation in a low-cost robotic platform.

Developed as part of the **EC6090 – Robotics and Automation Mini Project** at the **University of Jaffna**, this project focuses on building a fully autonomous robot by combining line-following navigation, obstacle avoidance, color-based decision-making, and pick-and-place functionality into a single embedded system.

---

## ⟡ Project Objectives

The main objectives of this project are:

- ⟢ To design and assemble a low-cost mobile robot using a smart car chassis
- ⟢ To implement autonomous line-following navigation
- ⟢ To detect and avoid static obstacles on the track
- ⟢ To identify colored objects using a color sensor
- ⟢ To perform a simple pick-and-place operation using a servo mechanism
- ⟢ To integrate multiple robotic subsystems into one autonomous platform
- ⟢ To develop structured and reliable embedded control logic for real-time operation

---

## ⚙️ System Functionality

The robot performs the following sequence of tasks:

1. ➜ Starts from the initial point and follows a predefined line path  
2. ➜ Detects obstacles placed on the track and avoids them  
3. ➜ Rejoins the line after obstacle avoidance  
4. ➜ Detects a green object placed on the path  
5. ➜ Activates the pick mechanism to collect the object  
6. ➜ Continues navigation toward the end zone  
7. ➜ Places or drops the object at the designated location  

---

## 🜂 Key Features

- 🛤️ Autonomous line-following navigation
- 🚧 Obstacle detection and avoidance
- 🌈 Color-based object identification
- 🦾 Servo-based pick-and-place mechanism
- 🧠 Embedded control using ESP32
- 📡 Real-time sensor integration
- 🔋 Fully autonomous operation without manual control during execution

---

## 🧩 Hardware Components

The robot is built using commonly available low-cost components. The hardware used in this project includes:

- 🔹 ESP32 microcontroller
- 🔹 Smart car chassis kit
- 🔹 DC motors and wheels
- 🔹 Motor driver module
- 🔹 IR line sensors
- 🔹 Ultrasonic sensor
- 🔹 Color sensor
- 🔹 Servo motors
- 🔹 Battery power supply

---

## 🖥️ Software and Control

The robot is programmed using embedded control logic to coordinate the behavior of all sensing and actuation modules. The software handles:

- ◈ Line sensor reading and path correction
- ◈ Obstacle detection and navigation adjustment
- ◈ Color recognition logic
- ◈ Servo control for picking and releasing objects
- ◈ Sequential task execution for full system integration

This project focuses on practical robotics implementation and does not rely on ROS, AI, or machine learning methods.

---

## 🗺️ Project Workflow

The overall workflow of the robot can be summarized as follows:

**Start → Line Following → Obstacle Detection → Obstacle Avoidance → Return to Line → Color Detection → Pick Object → Move to End Zone → Place Object → Stop**

---

## 🗂️ Repository Structure

```text
Line-Following-Robot/
│── code/
│   ├── main.ino
│   ├── line_following.ino
│   ├── obstacle_avoidance.ino
│   ├── color_detection.ino
│   └── servo_control.ino
│
│── docs/
│   └── images/
│          └── Setup.png
│
│── README.md
