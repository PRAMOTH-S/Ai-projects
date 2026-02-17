# AI Projects 🚀

This repository contains my **Artificial Intelligence / Machine Learning projects** and practice codes using **Python + OpenCV**.

---

## 📌 Projects Included

### 1) Object Detection and Tracking (HSV) 🎯
- Object tracking using HSV color space  
- Uses OpenCV + contour detection  
- Direction detection based on object position and radius  

---

### 2) HSV Color Calibration Tool 🎚️
- Tkinter GUI sliders for Hue, Saturation, Value  
- Helps to find correct HSV range for any color  
- Supports screenshot capture and webcam frame testing  

---

### 3) Real-Time Face Emotion Recognition 🎭📷
This project detects **human facial emotions in real-time** using a webcam or mobile camera (IP Webcam).  
It uses the **facial-emotion-recognition** library along with **OpenCV**.

#### Features
- Real-time emotion detection using laptop webcam  
- Emotion detection using Mobile IP Camera (IP Webcam)  
- Works in CPU mode (no GPU needed)  

---

### 4) Real-Time Object Detection using MobileNet SSD 🎯📷
This project performs **real-time object detection** using a webcam by loading a **pre-trained MobileNet SSD model** with OpenCV's DNN module.

It detects common objects like:
- person
- car
- dog
- chair
- bottle
- etc.

#### Features
✅ Real-time detection using laptop webcam  
✅ Uses OpenCV DNN (Deep Neural Network) module  
✅ Bounding box + confidence percentage shown  
✅ Fast and lightweight model (MobileNet SSD)

#### Model Used
- **MobileNet SSD**
- Framework: **Caffe**
- Files used:
  - `MobileNetSSD_deploy.prototxt.txt`
  - `MobileNetSSD_deploy.caffemodel`

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

## 📂 Project Files

| File Name | Description |
|----------|-------------|
| `main.py` | Object tracking program using HSV color range |
| `colorCalibrationforHSV.py` | HSV slider calibration GUI tool |
| `emotion.py` | Emotion recognition using laptop webcam |
| `emotion_with_ip.py` | Emotion recognition using mobile IP webcam |
| `ip.py` | Only displays IP webcam video stream |
| `object_detection_mobilenetssd.py` | Real-time object detection using MobileNet SSD |
| `MobileNetSSD_deploy.prototxt.txt` | MobileNet SSD model config file |
| `MobileNetSSD_deploy.caffemodel` | MobileNet SSD trained weights |

---

## ⚙️ Installation

### ✅ Install Requirements

```bash
pip install opencv-python numpy imutils pyautogui pillow
pip install torch torchvision
pip install facial-emotion-recognition
