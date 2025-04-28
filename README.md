Hand Gesture-Based Brightness Controller:

This project uses OpenCV, MediaPipe, and Screen Brightness Control to adjust your screen brightness by detecting the distance between your thumb and index finger in real time through your webcam.

Features:

1. Real-time hand tracking using your webcam.
2. Dynamic control of screen brightness by moving your fingers.
3. Smooth brightness adjustments without touching keyboard buttons.

Technologies:
1. Python 3.8+
2. OpenCV
3. MediaPipe
4. screen-brightness-control

How to Clone and Run This Project in VS Code
1. git clone https://github.com/your-username/hand-gesture-brightness-controller.git
Open a terminal inside VS Code and run
2. pip install opencv-python mediapipe screen-brightness-control
3. python your_filename.py

How It Works:
1. The webcam captures live video frames.
2. MediaPipe detects hand landmarks.
3. The distance between the thumb tip and index finger tip is measured.
4. This distance is mapped to a brightness percentage (0% to 100%).
5. The screen brightness is updated in real-time based on your hand gesture.

Usage:
1. Bring your thumb and index finger close together(lower brightness).
2. Move your thumb and index finger farther apart(increase brightness).
3. Press 'q' to exit the application.
