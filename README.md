# Pothole-and-Manhole-detection-using-YOLOv8
Road Defect Detection using YOLOv8

This project implements a deep learning-based object detection system for real-time identification of road defects such as potholes, manholes, and cracks. Using the YOLOv8 framework, the model is trained on a custom dataset and achieves high accuracy in detecting defects from both images and videos.

🚀 Features

Real-time detection of potholes, manholes, and cracks

Custom dataset collection and annotation

Image augmentation for improved model robustness

Training and fine-tuning of YOLOv8 for high accuracy

Works on both images and video streams

Potential applications in traffic safety and road maintenance systems

📂 Dataset

Images of road defects were collected and annotated using LabelImg.

Dataset was augmented with transformations (rotation, flipping, brightness, scaling) to improve generalization.

Organized in YOLO format (images/train, images/val, labels/train, labels/val).

🛠️ Tech Stack

Python 3.x

YOLOv8 (Ultralytics)

OpenCV – for video/image processing
📊 Results

Achieved high accuracy in real-time defect detection.

Model can detect multiple road defects simultaneously.

Tested on both static images and video streams.

🌍 Applications

Smart city infrastructure monitoring

Automated road maintenance systems

Traffic safety improvement

Support for autonomous vehicles

📌 Future Work

Deployment on edge devices (Jetson Nano, Raspberry Pi)

Integration with GIS mapping for defect localization

Expanding dataset with more road defect categories
PyTorch – deep learning backend

LabelImg – for annotation
