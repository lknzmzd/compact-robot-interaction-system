# Compact Robot Interaction System

A small-scale robotics prototype focused on servo-based motion, embedded control, and interactive behavior.

---

## 🔹 System Overview

This project explores how a compact robotic unit can simulate responsive behavior using simple hardware components.

The system combines embedded control (ESP32), servo-driven motion, and sensor input to create a basic interactive robot platform.

---

## 🔹 Hardware Architecture

- Microcontroller: ESP32-C3
- Actuators:
  - SG90 Servo Motors (for head / arm / movement)
- Power:
  - External battery (Li-ion / 600mAh)
- Output:
  - 1.3" TFT Display (optional for face/feedback)
  - Speaker (8Ω 0.5W)
- Sensors (tested or planned):
  - HC-SR602 (motion detection)
  - VL53L0X (distance sensing)
  - BH1750 (light sensing)

---

## 🔹 System Flow

Sensor Input → Control Logic → Motion Commands → Servo Output → Physical Interaction

---

## 🔹 Core Capabilities

- Basic servo movement (head / arms / rotation)
- Reactive behavior based on sensor input
- Simple visual/audio feedback
- Compact embedded design

---

## 🔹 Engineering Challenges

- Power instability when running multiple servos
- Limited space for wiring and component placement
- Servo jitter and calibration issues
- Synchronizing motion with sensor input

---

## 🔹 Solutions & Experiments

- Used external power to stabilize servo behavior
- Reworked internal wiring layout for compact design
- Iterative servo calibration for smoother motion
- Tested different sensor combinations for responsiveness

---

## 🔹 Current Status

Working prototype — motion and interaction behaviors under active development.

---

## 🔹 Media / Demonstration

(Real photos and videos soon)

---

## 🔹 Future Work

- Improved motion smoothness and coordination
- AI-based behavior layer
- Voice interaction
- Integration with external systems (JARVIS / control dashboard)
