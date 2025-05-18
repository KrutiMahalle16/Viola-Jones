# Viola-Jones
Face Detection using Viola-Jones Algorithm
This project implements face detection using the Viola-Jones algorithm with OpenCV in Python. Viola-Jones is one of the earliest and most popular real-time face detection methods, known for its speed and accuracy.

### 📌 What is the Viola-Jones Algorithm?
The Viola-Jones algorithm detects objects using:

Haar-like features for pattern recognition

Integral image for fast feature computation

AdaBoost for feature selection

Cascade Classifier for efficient multi-stage detection

It is primarily used for face detection in real-time applications.

### 🛠️ Technologies Used
Python 3.x
OpenCV (cv2)

### 🔄 Method Overview
Load the Haar cascade XML classifier from OpenCV.
Read the input image or video frame-by-frame.
Convert frames to grayscale for detection.
Apply detectMultiScale() to find faces.
Draw bounding boxes around detected faces.
📷 Sample Output
The output image/video will display rectangles around detected faces using the trained Haar cascade model.

✅ Conclusion
The Viola-Jones algorithm is an efficient and classic method for face detection in real-time systems. This project demonstrates its usage with OpenCV, offering a practical introduction to face detection in computer vision.





