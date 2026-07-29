# 🚀 YOLOv8 Object Detection and Multi-Object Tracking
C:/Users/saads/Pictures/Screenshots/Screenshot%202026-07-28%20064951.png
## 📌 Overview

This project performs **real-time object detection and multi-object tracking** on a video using **YOLOv8**, **ByteTrack**, **OpenCV**, and the **Supervision** library.

Each detected object is assigned a unique tracking ID that remains consistent across video frames.

---

## ✨ Features

- Detect objects using YOLOv8
- Multi-object tracking with ByteTrack
- Draw bounding boxes around detected objects
- Display:
  - Class Name
  - Confidence Score
  - Tracking ID
- Save the processed video automatically
- Display the processed frames during execution

---

## 🛠 Technologies Used

- Python
- OpenCV
- Ultralytics YOLOv8
- Supervision
- ByteTrack

---

## 📂 Project Structure

```text
YOLO-Tracking-Detection/
│
├── YOLO_Tracking_Detection.ipynb
├── yolov8n.pt
├── project.mp4
├── output.avi
├── README.md
```

---

## 📦 Installation

Install the required libraries:

```bash
pip install ultralytics
pip install supervision
```

---

## ▶️ How It Works

1. Load the YOLOv8 model.
2. Open the input video.
3. Detect objects in every frame.
4. Convert detections using Supervision.
5. Track detected objects with ByteTrack.
6. Draw bounding boxes and labels.
7. Save the output video.
8. Release resources after processing.

---

## 🖥 Output Information

Each detected object displays:

- Object Class
- Confidence Score
- Tracking ID

Example:

```text
person | 0.96 | ID:3
car | 0.91 | ID:7
```

---

## 📚 Libraries

```python
from ultralytics import YOLO
import supervision as sv
import cv2
```

---

## 📹 Output

The processed video is saved as:

```text
output.avi
```

---

## 📚 Concepts Used

- Computer Vision
- Object Detection
- Object Tracking
- Deep Learning
- YOLOv8
- ByteTrack
- OpenCV
