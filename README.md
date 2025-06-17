# 6th-finger-prosthetic-prototype-to-assist-stoke-patients

Robotic Sixth Finger

A wearable robotic sixth finger designed to augment human hand capabilities. The system integrates sensors, signal processing, and control logic to assist users in grasping or manipulating objects with enhanced dexterity.

Project Overview

This project aims to develop a *wearable robotic sixth finger* prototype that responds to muscle activity and pressure inputs. The robotic finger is designed to act as an assistive device for individuals with motor impairments or to augment tasks requiring additional grip.

Features

- Muscle and pressure-based control using *MyoWare Muscle Sensor* and *FlexiForce A301 Pressure Sensor*
- Signal processing using a *Hybrid Filtering Algorithm* (Median → Mean filtering)
- Prototyping and sensor testing using *Arduino Mega 2560*
- Control and wireless communication using *ESP32*
- Custom-designed *3D-printable CAD model* for finger mount
- Future-ready for integration with advanced prosthetics and assistive robotics

Components Used

| Component                 | Purpose                                      |
|---------------------------|----------------------------------------------|
| *ESP32*                 | Wireless communication & microcontroller     |
| *FlexiForce A301*       | Detects pressure from the fingertip          |
| *MyoWare Muscle Sensor* | Detects muscle activity (EMG) for actuation  |
| *Arduino Mega 2560*     | Used for sensor data testing and filtering   |
| *3D-Printed Finger*     | Custom prosthetic design for extra finger    |

Filtering Algorithm

We implemented a *hybrid filtering technique* to ensure reliable and noise-reduced sensor data:

1. *Median Filtering* – Removes outlier spikes from sensor input.
2. *Mean Filtering* – Smooths the signal after median filtering to reduce jitter and noise.

This ensures that the actuation of the sixth finger is *stable and responsive* to actual user input.

Project Development Stages

Completed:
- Initial prototyping using Arduino Mega 2560
- Sensor integration and testing (FlexiForce A301, MyoWare)
- Hybrid filtering algorithm implementation
- CAD model design for 3D printing the finger
- ESP32 integration for wireless control and data processing

 In Progress / Future Work:

- Servo motor integration for finger movement
- Final 3D print and mechanical assembly
- Real-time signal classification for dynamic response
- Wearable glove integration and user testing

 Use Cases

- Assistive robotic finger for motor-impaired individuals
- Human augmentation for specific tasks requiring extra grip
- Rehabilitation and physiotherapy research
- Experimental prosthetics and wearable robotics

Contributors

- *Nitish Dandu*
- *Sai Harsha*
- *Rahul Chowdary*
- *Salla Shivesh*

![Image](https://github.com/user-attachments/assets/b9a9d748-c2da-48d6-aa71-a440d37d7cc4)

