# Virtual-Mouse
Developed a virtual mouse using OpenCV and Python, allowing users to control the cursor and interact with their computer without a physical mouse. This project utilized computer vision to track hand movements in real-time, translating them into mouse movements and clicks.

Key Features:

Utilized OpenCV to capture real-time video feed from the webcam and process hand gestures for mouse pointer control.

Implemented hand detection using color-based segmentation and contour detection to identify hand position and movement.

Converted detected hand positions into cursor movements, simulating mouse actions such as left-click, right-click, and scrolling.

Integrated PyAutoGUI to simulate mouse events based on hand gestures and movement detection.

Supported multiple gestures for different mouse functions:

Fist gesture to simulate a left-click.

Open hand gesture for right-click and scrolling.

Index finger pointing gesture to track the cursor's position and simulate mouse movement.

Implemented real-time gesture recognition with low latency for smooth user interaction.

Designed for accessibility, allowing users to control a computer remotely or with physical limitations.

Technologies Used:
Python, OpenCV, PyAutoGUI, Numpy, Hand Gesture Recognition, Computer Vision, Real-time Video Processing
