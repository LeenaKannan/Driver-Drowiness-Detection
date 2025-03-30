# Driver-Drowiness-Detection
### Real-Time Driver Drowsiness Detection Using Raspberry Pi 4
## Introduction
Driver fatigue is a significant cause of road accidents, making drowsiness detection a crucial safety feature. This project focuses on developing a Real-Time Driver Drowsiness Detection System using Raspberry Pi 4 and computer vision techniques to monitor a driver’s alertness and prevent accidents caused by fatigue.

## Project Overview
This system utilizes a camera module connected to a Raspberry Pi 4 to capture real-time video frames of the driver's face. Using machine learning and deep learning algorithms, the system detects signs of drowsiness by analyzing eye closure, yawning frequency, and head position. If drowsiness is detected, the system triggers an alert mechanism such as a buzzer or voice alarm to wake up the driver.

## Key Features
✔ Real-time face and eye detection using OpenCV and Dlib
✔ Machine learning-based drowsiness detection via a trained CNN model
✔ Lightweight and power-efficient implementation for embedded systems
✔ Audio and visual alerts for immediate driver response
✔ Edge AI processing on Raspberry Pi without cloud dependency

## Technology Stack
🔹 Hardware: Raspberry Pi 4, Pi Camera Module, Buzzer/Speaker
🔹 Software: Python, OpenCV, Dlib, TensorFlow/Keras
🔹 Libraries & Frameworks: NumPy, Scikit-learn, OpenCV, Mediapipe
🔹 Model Used: Pre-trained CNN model for facial landmark detection

## Implementation Workflow
**Face & Eye Detection:**The system continuously detects the driver's face and tracks eye movement using OpenCV and Dlib.
**Drowsiness Detection Algorithm:**A deep learning model determines if the driver’s eyes are closed for an extended period, indicating fatigue.
**Yawning Detection:**The system monitors mouth movements to detect yawning as an additional drowsiness indicator.
**Alert Mechanism:**If the driver is drowsy, an alarm/buzzer is activated to regain attention.
**Performance Optimization: **The algorithm is optimized for real-time execution on Raspberry Pi 4.

## Applications
- **Vehicle Safety Systems** for personal and commercial vehicles
- **Public Transport Monitoring**to prevent accidents
- **Fleet Management Solutions** for logistics and delivery services

## Future Enhancements
- Integration with IoT for remote monitoring
- Adaptive learning for personalized drowsiness detection
- Expansion to multi-sensor detection (heart rate, blink rate)
This project aims to provide an affordable, real-time, and efficient drowsiness detection solution to improve road safety and reduce accidents caused by driver fatigue.
