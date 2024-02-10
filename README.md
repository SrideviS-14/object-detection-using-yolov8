# YOLO Real-time Object Detection with Text-to-Speech

## Overview
This Python project utilizes the YOLO (You Only Look Once) real-time object detection model to identify objects in a video feed from a camera. Detected object labels are then converted into speech using the Text-to-Speech (TTS) library `pyttsx3`.

## Tech Stack
- **OpenCV:** Library for computer vision and video processing.
- **PyTorch:** Deep learning framework (required by YOLO).
- **Ultralytics YOLO:** YOLO implementation for PyTorch.
- **pyttsx3:** Python library for Text-to-Speech.

## Installation
Ensure you have the required libraries installed:

```bash
pip install opencv-python
pip install pyttsx3
pip install git+https://github.com/ultralytics/yolov5.git
```

## Note
Ensure that the camera is connected and functional.
Adjust the YOLO confidence threshold (conf) as needed for your use case.
You may need to install additional dependencies based on your system configuration.
