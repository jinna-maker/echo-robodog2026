```md
# ECHO RoboDOG  
## หุ่นยนต์สุนัขอัจฉริยะเพื่อการตรวจวัดและตอบสนองด้านความปลอดภัย  
### A Smart Robot Dog for Modular Sensing and Safety Response

![Project Status](https://img.shields.io/badge/status-prototype-blue)
![Platform](https://img.shields.io/badge/platform-ESP32-green)
![Sensor](https://img.shields.io/badge/sensor-MQ135-orange)
![License](https://img.shields.io/badge/license-Open%20Source-lightgrey)

---

## 📌 Project Overview

**ECHO RoboDOG** is a small smart robot dog prototype designed for environmental sensing and safety response.  
The robot can detect abnormal air conditions such as poor air quality, gas, smoke, or unusual smell using an **MQ135 Gas Sensor**.

When abnormal air conditions are detected, the robot responds automatically by changing its behavior, such as:

- stopping movement
- sitting down
- barking
- showing an alert or angry face on the OLED screen

This project combines robotics, sensors, microcontroller programming, sound alerts, and 3D-printed mechanical design into a hands-on STEM learning prototype.

---

## 🇹🇭 ชื่อโครงงานภาษาไทย

**หุ่นยนต์สุนัขอัจฉริยะเพื่อการตรวจวัดและตอบสนองด้านความปลอดภัย**

## 🇬🇧 English Project Title

**A Smart Robot Dog for Modular Sensing and Safety Response**

---

## 👦 Student Information

| Item | Detail |
|---|---|
| Student | Jinna Arunplod |
| Grade | G4A |
| School | AIT International School |
| Project Type | Invention / Robot Prototype |
| Project Theme | Robotics, Air Sensing, Safety Response, STEM Learning |

---

## 🎯 Objectives

The main objective of this project is to develop a small robot dog prototype that can detect abnormal air conditions and respond in a clear and easy-to-understand way.

Project objectives:

1. Design and build a small robot dog prototype.
2. Use an **MQ135 Gas Sensor** to detect air quality or abnormal gas levels.
3. Use an **ESP32** microcontroller as the main controller.
4. Control robot movement using **servo motors** and a **PCA9685 Servo Driver**.
5. Create automatic responses such as stop, sit, bark, and alert display.
6. Support STEM and Maker Education through hands-on learning.
7. Design the robot as a modular platform for future sensor upgrades.

---

## 🧠 Project Concept

Some areas may contain hidden risks such as smoke, gas, poor air quality, or unsafe conditions.  
Direct inspection by humans may be dangerous, especially in closed rooms, laboratories, or unknown environments.

ECHO RoboDOG is designed as a small scouting robot that can check the environment before humans enter.  
It uses sensors to detect abnormal air conditions and responds using robot behavior, sound, and facial expression.

The basic idea is:

> **Sense → Detect → Alert → Respond**

---

## ⚙️ How It Works

The robot works in four main steps:

| Step | Description |
|---|---|
| **Sense** | The MQ135 sensor reads air quality or gas values. |
| **Detect** | ESP32 compares the sensor value with a defined threshold. |
| **Alert** | If the value is abnormal, the robot stops or sits. |
| **Respond** | The robot barks, shows an alert face, or displays status on the OLED screen. |

---

## 🤖 Robot Behaviors

### Normal Condition

When air quality is normal, the robot can:

- stand
- walk
- show a happy face
- play panting sound
- wait for command

### Abnormal Air Detected

When gas, smoke, or abnormal smell is detected, the robot can:

- stop moving
- sit down
- bark
- show angry or alert face
- warn the user

---

## 🔩 Main Components

| Component | Function |
|---|---|
| **ESP32 Microcontroller** | Main controller for reading sensors and controlling robot actions |
| **MQ135 Gas Sensor** | Detects air quality, gas, smoke, or unusual smell |
| **Servo Motor** | Controls robot movement and posture |
| **PCA9685 Servo Driver** | Controls multiple servo motors |
| **OLED Screen** | Displays robot face or system status |
| **Micro SD Card Module** | Stores sound files such as barking and panting |
| **MAX98357A Amplifier + Speaker** | Plays sound alerts |
| **3D Printed Body** | Robot dog structure designed for easy assembly and modification |

---

## 🧩 System Features

- Small robot dog prototype
- Air quality and gas detection using MQ135
- Automatic safety response
- Servo-based movement
- OLED face display
- Barking and alert sounds
- Modular 3D-printed body
- Easy to upgrade with more sensors
- Suitable for STEM and Maker Education

---

## 🧪 Initial Testing Result

From initial testing, the robot can read values from the MQ135 gas sensor and use them to decide its response.

When the sensor value is normal, the robot stays in normal mode.  
When the sensor value is higher than the defined threshold, the robot changes to alert mode.

In alert mode, the robot can:

- stop
- sit
- bark
- show an alert face

This shows that the robot can connect sensor data with physical and sound-based responses.

> Note: This project is still a learning prototype.  
> MQ135 values may be affected by temperature, humidity, gas type, and sensor warm-up time.  
> For real-world use, sensor calibration and further testing are required.

---

## 🌟 Key Features and Innovation

The key innovation of ECHO RoboDOG is the connection between environmental sensing and robot behavior.

Instead of only displaying numbers, the robot communicates using movement, sound, and facial expressions.  
This makes the system easier to understand, especially for students, children, and beginners.

Main innovations:

- Robot dog as an air-scouting platform
- Sensor-based automatic behavior
- Friendly and easy-to-understand warning system
- Modular design for future sensor upgrades
- Open-source learning concept
- 3D-printable structure
- Low-cost and accessible components

---

## 🚀 Future Development

This project can be improved in the future by adding:

- PM2.5 sensor
- smoke sensor
- temperature and humidity sensor
- CO2 sensor
- camera module
- wireless remote control
- mobile app or web dashboard
- AI / Edge Computing
- better walking stability
- data logging for air quality monitoring

---

## 📚 Educational Value

ECHO RoboDOG supports hands-on learning in:

- robotics
- electronics
- sensor technology
- microcontroller programming
- 3D design and 3D printing
- problem solving
- STEM and Maker Education

The project helps students understand how robots can sense the environment, make simple decisions, and respond automatically.

---

## 📝 Conclusion

ECHO RoboDOG demonstrates how a small robot can combine sensing, movement, sound, and automatic response to become a smart safety companion.

Although it is currently a prototype for learning and demonstration, it has strong potential for future development as:

- an environmental scout robot
- an air-quality alert robot
- a safety response robot
- an open-source STEM learning platform

---

## 🙏 Credits

Project by **Jinna Arunplod**  
AIT International School  

AI-assisted writing and documentation support.
```
