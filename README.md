# 👁️🖐️ AI Eye & Hand Gesture Control System  
### Hackathon Project 🚀

An AI-powered **touch-free computer control system** that allows users to control mouse movement, clicks, scrolling, and screen brightness using **eye movements and hand gestures**, all through a **single webcam**.

This project was built as part of the **RIFT Hackathon**.  
🔗 Hackathon Link: https://rift.pwioi.club/

---

## 📌 Project Overview

This project demonstrates how **Computer Vision and Artificial Intelligence** can be used to create an **assistive and accessibility-focused Human–Computer Interaction (HCI) system**.

Without using a mouse or keyboard, users can:
- Move the mouse using eye movement
- Click using eye blink
- Freeze mouse movement using a fist gesture
- Scroll using eye or head movement
- Control system brightness using finger pinch
- View live brightness percentage on screen

All actions are performed in **real time** using a **single camera window**.

---

## ✨ Features

- 👁️ Eye-controlled mouse movement  
- 👀 Blink-to-click (hands-free clicking)  
- ✊ Fist gesture to toggle freeze mode  
- 🧠 Eye / head movement scrolling in freeze mode  
- 🤏 Thumb–index pinch to control brightness  
- 📊 Live brightness percentage display  
- 🎥 Single webcam, real-time processing  
- ♿ Designed for accessibility and assistive technology  

---

## 🛠️ Tech Stack

- **Python**
- **OpenCV** – Camera handling & image processing
- **MediaPipe Face Mesh** – Eye & face landmark detection
- **MediaPipe Hands** – Hand gesture recognition
- **PyAutoGUI** – Mouse and scroll automation
- **screen-brightness-control** – System brightness control
- **NumPy** – Mathematical calculations & interpolation

---

## 🧠 System Workflow

1. Webcam captures live video frames
2. MediaPipe detects face and hand landmarks
3. Eye landmarks control mouse movement
4. Blink detection triggers mouse click
5. Fist gesture toggles freeze mode
6. Eye/head movement scrolls in freeze mode
7. Finger pinch controls brightness
8. Brightness percentage is displayed on screen

---

## ▶️ How to Run the Project

### 1️⃣ Create Environment
```bash
conda create -n eye_gesture_ai python=3.10 -y
conda activate eye_gesture_ai
pip install opencv-python mediapipe pyautogui numpy screen-brightness-control
python eye_hand_control_with_brightness.py

⚠️ Important:
Run the project as a .py file (not in Jupyter Notebook) for proper camera and GUI support.

🧪 Gesture Guide
Gesture	Action
Eye movement	Mouse movement
Left-eye blink	Mouse click
Fist	Freeze / unfreeze mouse
Eye movement (freeze mode)	Scroll
Thumb–index pinch	Brightness control
Press Q	Exit application
🎯 Applications

Assistive technology for people with motor disabilities

Touch-free computer interaction

Smart workspaces

AR/VR interfaces

Human–Computer Interaction (HCI) research

Hackathon & academic demonstrations

🏆 Hackathon

This project was developed for RIFT Hackathon.
🔗 https://rift.pwioi.club/

Special thanks to:

RIFT Hackathon organizers

PW IOI Club

Mentors and judges for guidance and support

📄 Documentation

📘 Project Explanation PDF
(Included in repository / shared separately for jury evaluation)

🤝 Collaboration

Open to collaboration, feedback, and improvements.
Feel free to fork this repository, raise issues, or suggest enhancements.

🧠 One-Line Impact Statement

Turning human intent into digital action — no touch required.
