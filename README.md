# AI Projects 🚀

This repository contains my **Artificial Intelligence / Machine Learning projects** and practice codes using **Python + OpenCV**.

---

## 📌 Projects Included

### 1) Object Detection and Tracking (HSV) 🎯
- Object tracking using HSV color space  
- OpenCV + contour detection  
- Direction detection based on object position and radius  

---

### 2) HSV Color Calibration Tool 🎚️
- Tkinter GUI sliders for Hue, Saturation, Value  
- Helps to find correct HSV range for any color  
- Webcam testing + screenshot capture  

---

### 3) Real-Time Face Emotion Recognition 🎭📷
Detects **human facial emotions in real-time** using webcam or Mobile IP camera.

**Features**
- Laptop webcam support  
- Mobile IP Webcam support  
- Works in CPU mode  

---

### 4) Real-Time Object Detection using MobileNet SSD 🎯📷
Real-time object detection using **OpenCV DNN** with a pre-trained **MobileNet SSD** model.

**Detects:** person, car, dog, chair, bottle, etc.

**Model Files**
- `MobileNetSSD_deploy.prototxt.txt`
- `MobileNetSSD_deploy.caffemodel`

---

### 5) Vehicle Detection using OpenCV (Haar Cascade) 🚗
Detects vehicles in real-time using **OpenCV + Haar Cascade**.

**Features**
- Real-time vehicle detection  
- Haar Cascade based detection  
- Bounding box output  

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

---

## 📂 Project Files

| File Name | Description |
|----------|-------------|
| `main.py` | Object tracking using HSV |
| `colorCalibrationforHSV.py` | HSV calibration GUI tool |
| `emotion.py` | Emotion recognition (webcam) |
| `emotion_with_ip.py` | Emotion recognition (IP webcam) |
| `ip.py` | IP webcam video stream |
| `object_detection_mobilenetssd.py` | Object detection using MobileNet SSD |
| `vehicle_detection.py` | Vehicle detection using Haar Cascade |
| `haarcascade_car.xml` | Haar Cascade model file |
| `MobileNetSSD_deploy.prototxt.txt` | MobileNet SSD config |
| `MobileNetSSD_deploy.caffemodel` | MobileNet SSD weights |

---

## ⚙️ Installation

```bash
pip install opencv-python numpy imutils pyautogui pillow
pip install torch torchvision
pip install facial-emotion-recognition
