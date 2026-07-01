# Air-Canvas-ML


**Computer Vision Project using OpenCV, Machine Learning, and MediaPipe**

Build an Air Canvas that lets users draw in the air using simple hand gestures. This project combines **OpenCV** for real-time video processing and **MediaPipe** for accurate hand landmark detection and tracking. By identifying fingertip movements, the system creates a virtual drawing experience, demonstrating practical applications of computer vision and machine learning.



## Methodology ⭐

1. Capture video frames from the webcam and convert each frame from BGR to HSV color space for efficient color processing.
2. Create a virtual canvas and display drawing tool options (such as color selection and clear canvas).
3. Initialize the MediaPipe Hand Detector to track a single hand for improved accuracy and performance.
4. Convert each frame to RGB and pass it to the MediaPipe model to detect hand landmarks.
5. Identify the index fingertip coordinates and store them continuously across successive frames.
6. Use the stored coordinates to draw smooth lines on both the live video feed and the virtual canvas, creating an air drawing    effect.

Requirements: Python 3, NumPy, OpenCV, and MediaPipe installed on your system.
