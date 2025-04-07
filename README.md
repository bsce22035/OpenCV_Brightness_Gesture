# Brightness Control with Hand Gestures using OpenCV
Control your screen brightness in real-time using simple hand gestures using openCV.<br/>

## Features
Real-time hand tracking. <br/>
Adjust brightness by changing distance between thumb and index finger. <br/>

##  Working.
This project uses a webcam to capture real-time video and employs MediaPipe to detect and track hand landmarks, specifically focusing on the tips of the thumb and index finger. By calculating the distance between these two points using the Euclidean distance formula, the program maps this distance to a screen brightness level between 0% and 100% using linear interpolation. As you move your fingers closer or farther apart, the brightness adjusts accordingly through the screen_brightness_control library.

