# 🖐️ Virtual Touch Control using Hand Tracking

##  Overview
This project implements a **virtual touch interface** using **computer vision and hand tracking** to control physical hardware.  
A camera detects the user’s hand in real time, and the position of the index finger is used to interact with **virtual buttons displayed on the screen**.

When a virtual button is “touched”, a corresponding **RGB LED (Red, Green, Blue)** connected to an Arduino is activated.

---

## Features
- Real-time hand tracking using MediaPipe  
- Virtual touch buttons on screen  
- Control of RGB LEDs using gestures  
- Contactless human-computer interaction  
- Integration between computer vision and embedded systems  

---
<img width="495" height="647" alt="Screenshot 2025-08-16 at 12 49 01 AM" src="https://github.com/user-attachments/assets/a372fced-6512-411c-8086-084ebe06c1a7" />

Install dependencies:
```bash
pip install opencv-python mediapipe pyfirmata
