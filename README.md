# Real-Time Object Detection using Machine Learning

This project implements a real-time object detection system using a pre-trained MobileNet SSD model with OpenCV's DNN module. It detects and labels objects in a live webcam video stream.

---

## Features
- Real-time object detection with webcam input
- Uses MobileNet SSD pre-trained model (Caffe)
- Displays detected objects with bounding boxes and confidence scores

---

## Tech Stack
- Python 3.x
- OpenCV
- imutils
- NumPy

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/arunkp7/Real-Time-Object-Detection.git
cd Real-Time-Object-Detection

---

## 2. Create a virtual environment (optional but recommended)

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate


### 3. Install dependencies

```bash
pip install opencv-python imutils numpy

### 4. Usage

```bash
Run the detection script with the required model files as arguments in the terminal:
"python real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel"

This command will open your webcam and start detecting objects in real time. Press q to quit.
