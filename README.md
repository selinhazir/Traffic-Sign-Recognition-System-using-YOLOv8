# 🚦 Traffic Sign Recognition System with YOLOv8

This repository contains a comprehensive implementation of a real-time traffic sign detection and classification system. The project leverages **YOLOv8** (You Only Look Once) architecture to identify various traffic signs with high precision, aimed at enhancing Advanced Driver Assistance Systems (ADAS).

## 📊 Project Overview
The system is designed to process road imagery and identify traffic signs (e.g., speed limits, warnings, and mandatory signs). By utilizing deep learning, the model can generalize across different lighting and weather conditions.

### Key Technical Milestones:
- **Architecture:** YOLOv8 (Ultralytics) for state-of-the-art object detection performance.
- **Environment:** Developed and trained in a cloud-based GPU environment (Google Colab).
- **Pipeline:** Automated data ingestion from Roboflow, model training, and inference testing.

## 🛠 Tech Stack
- **Language:** Python 3.x
- **Deep Learning:** `ultralytics` (YOLOv8), `torch` (PyTorch).
- **Data Handling:** `roboflow` API for seamless dataset integration.
- **Visualization:** `matplotlib` and `PIL` for displaying detection results.

## 🚀 Implementation Details
The training process involved:
1. **Data Ingestion:** Utilizing the Roboflow API to fetch the annotated traffic sign dataset.
2. **Model Initialization:** Loading pre-trained YOLOv8 weights to leverage transfer learning.
3. **Training:** Executed for multiple epochs to optimize Mean Average Precision (mAP).
4. **Validation:** Evaluating model performance on unseen test images to ensure reliability.



---
**Author:** Selin Hazır  
**Institution:** Gazi University, Computer Engineering
