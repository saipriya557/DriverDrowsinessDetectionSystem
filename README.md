# DriverDrowsinessDetectionSystem

The Driver Drowsiness Detection System is a real-time computer vision and deep learning application designed to monitor drivers’ alertness and prevent accidents caused by drowsiness. It detects when the driver’s eyes are closed for a prolonged period and triggers an alarm to alert them.This project uses a combination of image preprocessing, deep learning, and OpenCV-based video analysis to achieve accurate detection, even under varying lighting conditions.

Features:
Real-time monitoring of driver’s eye state.
Detects drowsiness based on eye closure duration.
Alerts the driver using an audible alarm.
Lightweight and efficient for real-time performance.

Technologies Used:
Programming Language: Python
Computer Vision: OpenCV
Deep Learning: Convolutional Neural Network (CNN), Keras
Audio Alerts: Pygame

How It Works?
Face and Eye Detection: Using Haar Cascade classifiers to detect the driver’s face and eyes.
Eye State Classification: The CNN model predicts whether the eyes are open or closed.
Drowsiness Alert: If the eyes remain closed for a certain duration, an alarm is triggered in real time.
