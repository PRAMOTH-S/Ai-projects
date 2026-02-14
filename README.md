# AI Projects 🚀

This repository contains my **Artificial Intelligence / Machine Learning projects** and practice codes using **Python + OpenCV**.

---

## 📌 Projects Included

### 1) Object Detection and Tracking (HSV) 🎯
- Object tracking using HSV color space
- Uses OpenCV + contour detection
- Direction detection based on object position and radius

---

### HSV Color Calibration Tool 🎚️
- Tkinter GUI sliders for Hue, Saturation, Value
- Helps to find correct HSV range for any color
- Supports screenshot capture and webcam frame testing

---

### 2) Real-Time Face Emotion Recognition 🎭📷
This project detects **human facial emotions in real-time** using a webcam or mobile camera (IP Webcam).  
It uses the **facial-emotion-recognition** library along with **OpenCV**.

#### Features
- Real-time emotion detection using laptop webcam
- Emotion detection using Mobile IP Camera (IP Webcam)
- Works in CPU mode (no GPU needed)

---

## 🛠️ Tech Stack
- Python
- OpenCV
- NumPy
- Tkinter
- imutils
- pyautogui
- Pillow
- Torch + Torchvision
- facial-emotion-recognition
- urllib (for IP camera)

---

## 📂 Files

| File Name | Description |
|----------|-------------|
| `main.py` | Object tracking program using HSV color range |
| `colorCalibrationforHSV.py` | HSV slider calibration GUI tool |
| `emotion.py` | Emotion recognition using laptop webcam |
| `emotion_with_ip.py` | Emotion recognition using mobile IP webcam |
| `ip.py` | Only displays IP webcam video stream |

---

## ⚙️ Installation

### 1) Install Requirements
```bash
pip install opencv-python numpy imutils pyautogui pillow
pip install torch torchvision facial-emotion-recognition
