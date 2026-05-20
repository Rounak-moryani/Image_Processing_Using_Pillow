# Face Detection Using OpenCV

## Overview
This project is a real-time face detection system built using Python and OpenCV. It detects human faces from static images as well as live webcam video streams using OpenCV’s pre-trained Haar Cascade classifier.

The project is lightweight, fast, and beginner-friendly, making it a great introduction to computer vision concepts.

---

## Features
- Face detection using OpenCV Haar Cascade
- Supports image input
- Supports real-time webcam/video feed
- Draws bounding boxes around detected faces
- Fast and lightweight execution
- Easy to customize and extend

---

## Technologies Used
- Python
- OpenCV (cv2)
- NumPy

---

## Project Workflow
1. Load Haar Cascade classifier
2. Read image or webcam stream
3. Convert frame to grayscale
4. Detect faces using `detectMultiScale()`
5. Draw bounding boxes around detected faces
6. Display output in real time

---

## Installation

### Clone Repository
```bash
git clone https://github.com/your-username/face-detection-opencv.git
cd face-detection-opencv
