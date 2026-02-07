# Face Mask and Temperature Detection with Door Lock and Alert System

## Overview
This project implements a **real-time smart safety and access control system** that automatically verifies **face mask compliance** and **body temperature** before granting entry. The system integrates **computer vision**, **edge computing**, and **IoT hardware** to enable contactless access control, while providing **inclusive visual and auditory alerts** for deaf and blind users.

---

## Problem Statement
During the COVID-19 pandemic, enforcing safety measures such as mask-wearing and temperature screening in public spaces relied heavily on manual checks. This approach was inefficient, increased exposure risk, and often lacked accessibility for individuals with hearing or visual impairments.

---

## Solution
A **fully automated, contactless entry system** was designed and implemented to:
- Detect face masks using computer vision
- Measure body temperature using non-contact sensors
- Control door access based on safety compliance
- Provide LED (visual) and buzzer (auditory) alerts for accessibility

The system runs on **Raspberry Pi** for low-latency, edge-based decision-making.

---

## Key Features
- **Real-time face mask detection** using OpenCV and TensorFlow
- **Non-contact temperature monitoring** with configurable thresholds
- **Automated door lock control** based on detection results
- **Inclusive alert system**:
  - LED indicators for deaf users
  - Buzzer alerts for blind users
- **Edge computing architecture** for fast, offline processing
- Compact and deployable hardware setup for entry points

---

## Key Contributions
- Developed a face mask detection model using **Python, TensorFlow, and OpenCV**
- Integrated **Raspberry Pi** and **Pi Camera** for on-device image processing
- Implemented temperature sensing using **IR sensors** with safety threshold logic
- Designed an automated **door locking mechanism** controlled by detection output
- Built visual (LED) and auditory (buzzer) alerts to support accessibility
- Achieved **95%+ accuracy** in real-time mask detection across varied lighting and user positions
- Tested system reliability under multi-user and changing environmental conditions

---

## Engineering Practices
- Applied **edge computing principles** to minimize latency and dependency on cloud services
- Used **modular hardware design** with GPIO interfacing for sensors, LEDs, buzzer, and lock
- Conducted system-level testing for accuracy, responsiveness, and robustness
- Maintained version control and documentation using GitHub

---

## Tech Stack

### Software
- Python
- OpenCV
- TensorFlow

### Hardware
- Raspberry Pi
- Pi Camera
- IR Temperature Sensor
- Door Lock Mechanism
- LED
- Buzzer

### Concepts
- Computer Vision
- Real-Time Processing
- Internet of Things (IoT)
- Edge Computing
- Accessibility Engineering

---

## Impact
- Automated COVID-19 safety compliance at controlled entry points
- Reduced manual intervention and improved user safety
- Enhanced accessibility for hearing and visually impaired individuals
- Provided a scalable and deployable solution for public spaces

---

## Project Duration
**Jan 2022 – May 2022**
