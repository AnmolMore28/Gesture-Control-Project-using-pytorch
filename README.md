# Gesture-Control-with-TensorFlow-and-OpenCV
## Overview
This project leverages TensorFlow, OpenCV, and MediaPipe to detect hand gestures in real-time and trigger specific actions. It's a fun and interactive application of computer vision and deep learning.

---

## Features
- Real-time hand gesture recognition using webcam.
- Customizable actions for recognized gestures.
- Extendable to train and add new gestures.

---

## How It Works
1. Mediapipe detects hand landmarks.
2. TensorFlow predicts the gesture based on the landmarks.
3. OpenCV displays the recognized gesture in real-time.
4. Python libraries like `pyautogui` trigger actions (e.g., controlling volume).

---

## Setup

### 1. Install Dependencies
```bash
pip install tensorflow opencv-python mediapipe pyautogui
