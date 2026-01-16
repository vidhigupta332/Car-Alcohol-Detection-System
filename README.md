# 🚗 Car Alcohol Detection System (IoT Project)

An IoT-based embedded system designed to prevent drunk driving by detecting alcohol
in the driver's breath and automatically disabling vehicle ignition.

---

## 📌 Project Overview

Drunk driving is one of the major causes of road accidents worldwide.
This project implements an automated alcohol detection mechanism using an
MQ-3 alcohol sensor and Arduino Uno. If alcohol concentration exceeds a
safe threshold, the vehicle ignition is locked and alerts are triggered.

---

## 🎯 Aim

To design and develop a prototype alcohol detection system that prevents
vehicle operation when alcohol is detected in the driver’s breath.

---

## 🔑 Key Features

- Real-time alcohol detection using MQ-3 sensor
- Automatic engine lock (motor simulation)
- LCD display for system status
- Buzzer alert for unsafe condition
- Threshold-based decision making
- Continuous monitoring
- Low-cost and scalable design

---

## 🧠 Working Principle

1. MQ-3 sensor detects alcohol vapors from breath
2. Sensor sends analog value to Arduino
3. Arduino compares value with preset threshold (50%)
4. If alcohol detected:
   - Motor OFF (car locked)
   - Buzzer ON
   - LCD displays warning
5. If safe:
   - Motor ON
   - Normal LCD display

---

## 🧰 Hardware Components

- Arduino Uno
- MQ-3 Alcohol Sensor
- 16x2 LCD (I2C)
- DC Motor (engine simulation)
- Relay Module
- Buzzer
- Breadboard
- Power Supply

---

## 💻 Software Used

- Arduino IDE
- Embedded C / Arduino C
- LiquidCrystal_I2C Library

---

## 📂 Repository Structure

