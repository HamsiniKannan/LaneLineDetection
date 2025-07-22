# 🛣️ Lane Line Detection
Developed an algorithm to reliably detect and track lane lines in real-time video streams  under varying road and lighting conditions. Utilized Python and OpenCV for image  processing techniques like grayscale conversion, Canny edge detection, region of  interest masking, and Hough Transform to accurately identify lane boundaries.

## 📌 Overview:
This project uses computer vision techniques to detect lane lines on roads in both images and video streams. The goal is to identify and highlight lane boundaries for use in self-driving systems or driver-assist applications.

## ✨ Key Features
Detect lane lines in road images

Process full driving videos frame-by-frame

Overlay detected lanes back on original media

Visualizes intermediate image processing stages

Region of Interest masking for focused lane detection

Smooth detection using Hough Transform

## 🧠 Techniques Used
Grayscale conversion

Gaussian Blur for noise reduction

Canny Edge Detection

Region of Interest (ROI) Masking

Hough Line Transform

Image/video processing using OpenCV

Frame-by-frame video processing with moviepy

## 🖼️ Sample Images
Original Image

<img width="552" height="327" alt="image" src="https://github.com/user-attachments/assets/854ec638-658c-4767-b602-b8b4d9f68cc3" />

Grayscale

<img width="552" height="327" alt="image" src="https://github.com/user-attachments/assets/d9f88da3-ba3d-4bad-944d-a48bd449f5b1" />

Gaussian Blur

<img width="552" height="327" alt="image" src="https://github.com/user-attachments/assets/08646cfb-32b1-4cc1-89bf-5aafcc78ed79" />

Canny Edges

<img width="552" height="327" alt="image" src="https://github.com/user-attachments/assets/b47919a9-1b74-4c46-b3ac-c92e2a2c47ba" />

ROI Mask Applied

<img width="552" height="327" alt="image" src="https://github.com/user-attachments/assets/3450bd31-1e1f-43b5-baf7-e7d44347c41f" />

Hough Lines

<img width="552" height="327" alt="image" src="https://github.com/user-attachments/assets/659d3b8d-c279-483f-aaf2-fe8acaa43a94" />

Final Output

<img width="552" height="327" alt="image" src="https://github.com/user-attachments/assets/3326f21a-3010-476e-98ce-dca83f5eedfe" />

## 🔍 How it Works
Load image/video

Convert to grayscale

Apply Gaussian blur

Perform Canny edge detection

Apply a polygon mask for ROI

Use Hough Transform to detect lines

Overlay lines on original media

## 📦 Requirements
Python 3.x

OpenCV

NumPy

Matplotlib

MoviePy

Jupyter Notebook (for demo)

## 🔗 Related Topics
Autonomous Driving

Advanced Lane Finding

Image Processing Pipelines

Real-time CV Applications

OpenCV Hough Transform Tutorial

Edge Detection Techniques


## ✅ Summary
This project is a clean and modular implementation of lane detection, useful for learning computer vision or as a base for more advanced autonomous vehicle systems. All major vision steps are visualized for clarity and better debugging.

