# 🚶 Moving Object Detection Syste

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![Status](https://img.shields.io/badge/Status-Active-success)

---

## 📌 Overview
This project implements a **real-time moving object detection system** using **OpenCV and Python**.  
It detects motion in video streams by analyzing frame differences and highlighting moving regions with bounding boxes.

The system is lightweight, efficient, and suitable for real-world applications like surveillance and traffic monitoring.

---

## 🚀 Features
- 🎥 Real-time motion detection (Webcam & Video)
- 🧠 Frame differencing technique
- 📦 Contour detection with bounding boxes
- ⚡ Fast and CPU-efficient
- 🔄 Works with live and recorded video streams

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** OpenCV, NumPy  

---

## ⚙️ Working Principle
1. Capture consecutive video frames  
2. Convert frames to grayscale  
3. Apply Gaussian blur to reduce noise  
4. Compute frame difference  
5. Apply thresholding  
6. Detect contours  
7. Draw bounding boxes on moving objects  

---

## 📂 Project Structure
