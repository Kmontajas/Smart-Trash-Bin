# ♻️ AI-Enabled Smart Trash Bin
### Automatic Waste Classification and Proper Segregation

## 📖 About the Project

The **AI-Enabled Smart Trash Bin** is an educational project that explores how Artificial Intelligence (AI), the Internet of Things (IoT), and embedded systems can be used to improve waste management and promote proper waste segregation.

The project is designed to identify and classify waste into three categories: **biodegradable, non-biodegradable, and recyclable**. Using a camera, an AI-based image classification model, sensors, and servo motors, the system aims to automate waste segregation and monitor the condition of trash bins.

It also incorporates a digital monitoring system that allows authorized users to view bin statuses, classification records, alerts, and maintenance activities.

This project demonstrates how emerging technologies can be applied to real-world environmental challenges, particularly in educational institutions.

## 🎯 Objectives

- Promote proper waste segregation and environmental awareness.
- Explore the application of AI in waste image classification.
- Demonstrate the integration of hardware and software in an IoT-based system.
- Automate trash bin lid control using sensors and servo motors.
- Monitor bin capacity and provide alerts when bins are full.
- Introduce students to practical applications of AI, embedded systems, and database technologies.

## ✨ Key Features

- **AI-Based Waste Classification** — Identifies waste as biodegradable, non-biodegradable, or recyclable.
- **Automatic Waste Segregation** — Uses servo motors to control the appropriate bin compartment.
- **Bin Capacity Monitoring** — Uses ultrasonic sensors to monitor waste levels.
- **Alerts and Notifications** — Helps notify authorized personnel when bins require attention.
- **Digital Dashboard** — Displays bin status, classification records, and maintenance information.
- **Data Management** — Uses database services to store and synchronize system records.

## 🛠️ Technologies Used

- **Artificial Intelligence:** TensorFlow, TensorFlow Lite, and MobileNetV2
- **Computer Vision:** OpenCV
- **Microcontrollers:** ESP32 and ESP32-CAM
- **Sensors and Actuators:** HC-SR04 ultrasonic sensors and SG90 servo motors
- **Backend Development:** Node.js and Express
- **Database and Cloud Services:** MongoDB and Firebase
- **Application Development:** Flutter and Dart
- **Programming Languages:** Python, JavaScript, C/C++, and Dart

## ⚙️ How It Works

The system captures an image of a waste item using the ESP32-CAM. The AI classification component analyzes the image and determines the predicted waste category. Based on the classification result, the controller activates the appropriate servo motor to open the corresponding bin compartment.

Ultrasonic sensors monitor the bin's fill level, while Firebase and the backend services support data communication, record management, and dashboard updates.

## 🎓 Educational Purpose

This project serves as a practical learning resource for students interested in:

- Artificial Intelligence and Machine Learning
- Image Recognition and Computer Vision
- Internet of Things (IoT)
- Microcontroller Programming
- Hardware and Software Integration
- Mobile and Dashboard Application Development
- Database Management and Cloud Computing
- Sustainable Technology and Environmental Protection

It demonstrates how different computing technologies can work together to develop a solution to a real-world problem.

## 🌱 Project Significance

The project aims to encourage responsible waste disposal and improve awareness of proper waste segregation. It also provides an example of how intelligent systems can support environmental sustainability in schools and other community settings.

As an educational prototype, its classification accuracy and operational performance depend on factors such as image quality, lighting conditions, sensor reliability, and the AI model's training data.

## 🏫 Project Information

**Institution:** Unida Christian Colleges (UCC)

**Course:** IT 305 — Application Development and Emerging Technologies

**Project Type:** Educational Prototype / Research Project

**Project Date:** December 2025

## 📄 License

No license has been specified for this project. Please refer to the repository owner for permissions regarding the use or distribution of the source code.
