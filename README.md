THIS IS THE PROJECT WHICH USES OPENCV FOR AUTONOMOUSLY TAKES SCREENSHOT THROUGH HAND MOVEMENT AND PREVIEWS IT.

FEATURES: 
Opens webcam feed with real-time display.

Shows two static boxes on screen indicating where to place your hands.

Uses background subtraction and contour detection to identify hands inside each box.

Calculates the distance between detected hand centroids inside the two boxes.

Automatically captures a screenshot when hands come close to each other.

Screenshot preview window displayed upon capture.

Ability to reset screenshot capture and take multiple screenshots.

Simple, dependency-light approach avoiding MediaPipe for hand detection.


Requirements:

Python 3.x
OpenCV (cv2)
NumPy

Notes: 

The program uses background subtraction which works best with stable lighting and plain backgrounds.
This method offers a simpler alternative to MediaPipe but may have varying accuracy depending on conditions.
For best results, ensure hands are well separated from the background and move steadily inside the boxes.
