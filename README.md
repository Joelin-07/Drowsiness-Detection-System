## Drowsiness-Detection-System
This project aims to detect drowsiness using computer vision techniques. It monitors the person's face in real-time through a webcam feed and alerts if signs of drowsiness or sleepiness are detected.

### Requirements
1. OpenCV
2. NumPy
3. Dlib
4. Pygame

**Install above required packages**


Note: for dlib package, if you're encountering any error while installiing, download and save "dlib-19.24.1-cp311-cp311-win_amd64.whl" file to your "C:\Users\Joelin\dlib-19.24.1-cp311-cp311-win_amd64.whl" and then again try to install dlib package. * *This file will work for Python 3.11 versions* *


You need to download "shape_predictor_68_face_landmarks.dat" file for facial detection. Without this file, data for facial detection which dlib uses won't work.

### Features
1. Real-time face detection using OpenCV
2. Face landmark detection with Dlib
3. Analysis of eye blinks to determine drowsiness levels
4. Audio alarm for alerting when drowsiness is detected
5. Simple and intuitive Python implementation
