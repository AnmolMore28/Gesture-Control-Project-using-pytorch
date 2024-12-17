# Gesture Control Project 🎯

This project uses **Computer Vision** and **PyTorch** to control system functionalities like adjusting volume or launching applications via hand gestures.

## Features
- Real-time gesture recognition using a webcam.
- Control volume (up/down) and launch applications like Chrome or Calculator.
- Pre-trained PyTorch model for gesture classification.

## How It Works
1. **Data Collection**:
   - Collect hand landmarks using `mediapipe`.
   - Save landmarks to a CSV file for training.

2. **Model Training**:
   - Train a neural network with PyTorch for gesture classification.
   - Save the trained model as `gesture_model.pth`.

3. **Real-Time Control**:
   - Use the trained model for live gesture prediction.
   - Trigger actions based on recognized gestures.

## Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/AnmolMore28/Gesture-Control-Project-using-pytorch.git
