# Smart-Drone-Project
IoT + embedded system project to automate pesticide spraying using image processing.
 Smart Pesticide Spraying Drone

This project is a smart agricultural drone system designed to detect diseased crops using a camera and machine learning, and spray the appropriate pesticide from one of four tanks autonomously. It combines embedded systems, image processing, and drone flight control for precision farming.

## 📌 Objective

To automate the process of identifying diseased crop regions and spraying pesticides efficiently using an embedded system-based quadcopter.

## 🧠 Technologies Used

- **Microcontroller**: Raspberry Pi 4
- **Flight Controller**: KK2.1.5
- **Programming Language**: Embedded C, Python (for image processing)
- **Camera Module**: USB/CSI camera
- **Other Components**: 
  - 4-channel Relay Module
  - 4 Spray Nozzles with Pumps
  - Brushless Motors + ESC
  - Battery + Power Distribution
  - Step-down converter
- **Protocols**: GPIO control, PWM for motors

## ⚙️ Working

1. The drone captures images of crops using a mounted camera.
2. A machine learning model running on Raspberry Pi processes the images to detect signs of disease.
3. Based on the identified disease type, one of the four pesticide tanks is selected.
4. The relay module activates the corresponding pump to spray pesticide via a nozzle.
5. The KK2.1.5 controller ensures flight stability and movement over the crop area.

## 🔍 Features

- Real-time crop disease detection using image processing
- Multi-tank control for different types of pesticides
- Autonomous spraying based on detection
- Embedded system integration for flight and spraying control

## 🧪 Future Improvements

- Integrate GPS for precision mapping
- Add obstacle avoidance sensors
- Upgrade to STM32 for real-time sensor processing
- Train model on a larger disease dataset

## 🧑‍💻 Developed By

**Ahamad Fahiz**  
B.E. Electronics and Communication Engineering  
CDAC Embedded & IoT Intern | PA College of Engineering  
Email: frahmedfayiz@gmail.com


