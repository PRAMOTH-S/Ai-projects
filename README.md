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

### Install Requirements
```bash
pip install opencv-python numpy imutils pyautogui pillow
pip install torch torchvision facial-emotion-recognition


###3) 🎭 Real-Time Face Emotion Recognition (Webcam + Mobile IP Webcam)

This project detects **human facial emotions in real-time** using a live camera feed.  
It supports both:

✅ **Laptop Webcam**  
✅ **Mobile Camera (IP Webcam App)**  

It uses the **facial-emotion-recognition** library along with **OpenCV** to recognize emotions from facial expressions.

---

## 📌 Features
- Real-time emotion detection
- Works with laptop webcam
- Works with mobile IP Webcam
- Runs in **CPU mode** (No GPU needed)
- Displays emotion labels live on video feed

---

## 🧰 Technologies / Libraries Used
- Python
- OpenCV
- facial-emotion-recognition
- Torch + Torchvision
- NumPy
- Imutils

---

## 💻 Requirements
- Python 3.8+
- Laptop with webcam (or external webcam)
- (Optional) Android mobile phone with IP Webcam app
- Same WiFi network (for IP Webcam mode)

---

## 🔧 Installation

Install all required libraries:

```bash
pip install torch torchvision
pip install opencv-python
pip install facial-emotion-recognition
pip install numpy imutils

