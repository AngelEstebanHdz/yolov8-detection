# YOLOv8 Real-Time Object Detection

Real-time object detection using YOLOv8 and OpenCV. Detects objects through a webcam feed and draws bounding boxes with confidence scores.

## Demo

![Demo](demo.png)

## Requirements

- Python 3.8+
- Webcam (physical or virtual, e.g. DroidCam)

## Installation

```bash
pip install ultralytics opencv-python
```

## Usage

```bash
python "YOLO prueba.py"
```

Press `Q` to close the window.

## How it works

- Captures live video from webcam using OpenCV
- Runs each frame through YOLOv8n (nano model, optimized for speed)
- Draws bounding boxes and confidence scores in real time
- Runs on GPU if available (CUDA), falls back to CPU

## Model

Uses `yolov8n.pt` — the YOLOv8 nano variant. Lightweight and fast, ideal for real-time inference on consumer hardware.
