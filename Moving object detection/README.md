# 🚶 Moving Object Detection using OpenCV

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![Status](https://img.shields.io/badge/Status-Active-success)

---

## 📌 Overview
This project implements a **real-time moving object detection system** using **Computer Vision with OpenCV**.

The system detects motion by comparing the current video frame with an initial reference frame (background model). Any significant difference is treated as a moving object and highlighted with bounding boxes.

This project is inspired by fundamental computer vision concepts such as:
- Frame differencing  
- Image preprocessing (Grayscale, Gaussian Blur)  
- Thresholding & contour detection  

> 📂 Reference Materials:  
> - Workshop PPT: :contentReference[oaicite:0]{index=0}  
> - Implementation Code: :contentReference[oaicite:1]{index=1}  

---

## 🚀 Features
- 🎥 Real-time motion detection using webcam  
- 🧠 Background subtraction using first frame reference  
- 📦 Contour-based object detection  
- 🖼️ Bounding boxes for detected motion  
- ⚡ Lightweight and runs on CPU  
- 📝 Status display (Normal / Moving Object Detected)

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:**  
  - OpenCV  
  - imutils  
  - time  

---

## ⚙️ Working Principle

1. Capture live video stream from webcam  
2. Resize frame for consistent processing  
3. Convert frame to grayscale  
4. Apply Gaussian Blur to reduce noise  
5. Store the first frame as background reference  
6. Compute absolute difference between current frame and background  
7. Apply thresholding to highlight motion regions  
8. Perform dilation to fill gaps  
9. Detect contours  
10. Draw bounding boxes for significant movement  

---

## 📂 Project Structure
