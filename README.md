# Protecto
PPE-Detection System
Overview

In manufacturing industries, Personal Protective Equipment (PPE) such as helmets, safety harnesses, and goggles play a crucial role in ensuring worker safety. However, accidents still occur due to negligence and ineffective supervision.

This project leverages existing CCTV camera infrastructure along with YOLOv3 for PPE detection and DeepSORT for tracking workers in real-time. If a worker is found without the required PPE for more than a specified duration (e.g., 5 seconds), an alert is raised to notify the supervisor.
# Features

Real-time PPE detection using YOLOv3.
Multi-object tracking using DeepSORT.
Alert system for violations based on time threshold.
Works with existing CCTV feeds to minimize additional setup costs.

# Tech Stack

Python (Primary language)
YOLOv3 (Object detection)
DeepSORT (Object tracking)
OpenCV (Computer vision tasks)
TensorFlow/Keras (Deep learning framework)
Flask (optional) for a web-based alert system

# How It Works

Input Processing
The system takes live feed/video input from CCTV cameras.
Detection & Tracking
YOLOv3 detects workers and classifies PPE compliance.
DeepSORT assigns unique IDs to track individuals across frames.
Violation Alert
If a worker is detected without PPE for more than 5 seconds, an alert is triggered.

# Future Enhancements
Implementing real-time alert notifications via SMS or email.
Enhancing detection accuracy with custom-trained models.
Developing a web-based dashboard for monitoring violations.

Contributors

This project was developed as part of a team effort by:

[Mayank Sharma] - Model Implementation & Tracking

[Meghna Sharma] - Data Processing & Alerts

[Shivansh] - Backend Integration & Deployment
