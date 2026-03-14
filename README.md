# AI Projects 🚀

This repository contains my **Artificial Intelligence / Machine Learning projects** using **Python + OpenCV**.

---

## 📌 Projects Included

### 1) Object Detection and Tracking (HSV) 🎯
- Object tracking using HSV color space  
- OpenCV + contour detection  
- Direction detection based on object position  

---

### 2) HSV Color Calibration Tool 🎚️
- Tkinter GUI sliders for HSV values  
- Helps find correct color range  
- Webcam + screenshot support  

---

### 3) Real-Time Face Emotion Recognition 🎭📷
- Detects human emotions in real-time  
- Supports webcam & mobile IP camera  
- Works on CPU  

---

### 4) Object Detection using MobileNet SSD 🎯📷
- OpenCV DNN-based detection  
- Detects: person, car, dog, chair, bottle  

**Model Files**
- `MobileNetSSD_deploy.prototxt.txt`
- `MobileNetSSD_deploy.caffemodel`

---

### 5) Vehicle Detection (Haar Cascade) 🚗
- Real-time vehicle detection  
- Haar Cascade model  
- Bounding box output  

---

### 6) License Plate Recognition (LPR) 🚘

Detect and read vehicle number plates using **OpenCV + Tesseract OCR**.

**Features**
- Canny Edge Detection  
- Contour-based plate detection  
- OCR text extraction  

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
- pytesseract  
- facial-emotion-recognition  

---

## 📂 Project Files

| File Name | Description |
|----------|-------------|
| `main.py` | HSV object tracking |
| `colorCalibrationforHSV.py` | HSV calibration tool |
| `emotion.py` | Emotion detection (webcam) |
| `emotion_with_ip.py` | Emotion detection (IP cam) |
| `object_detection_mobilenetssd.py` | MobileNet SSD detection |
| `vehicle_detection.py` | Vehicle detection |
| `lpr.py` | License plate recognition |
| `haarcascade_car.xml` | Haar Cascade model |
| `MobileNetSSD_deploy.prototxt.txt` | Model config |
| `MobileNetSSD_deploy.caffemodel` | Model weights |

---

## ⚙️ Installation

```bash
pip install opencv-python numpy imutils pyautogui pillow
pip install torch torchvision
pip install pytesseract
pip install facial-emotion-recognition
