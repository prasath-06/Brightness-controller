Hand Gesture-Based Brightness Controller:

This project uses OpenCV, MediaPipe, and Screen Brightness Control to adjust your screen brightness by detecting the distance between your thumb and index finger in real time through your webcam.

Features
Real-time hand tracking using your webcam.
Dynamic control of screen brightness by moving your fingers.
Smooth brightness adjustments without touching keyboard buttons.

Technologies Used
Python 3.8+
OpenCV
MediaPipe
screen-brightness-control

How to Clone and Run This Project in VS Code
1. git clone https://github.com/your-username/hand-gesture-brightness-controller.git
Open a terminal inside VS Code and run
2. pip install opencv-python mediapipe screen-brightness-control
3. python your_filename.py

How It Works
The webcam captures live video frames.
MediaPipe detects hand landmarks.
The distance between the thumb tip and index finger tip is measured.
This distance is mapped to a brightness percentage (0% to 100%).
The screen brightness is updated in real-time based on your hand gesture.

Usage
Bring your thumb and index finger close together(lower brightness).
Move your thumb and index finger farther apart(increase brightness).
Press 'q' to exit the application.
