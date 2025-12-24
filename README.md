# DCSASS – YOLO-Based Video Surveillance Activity Detection

This project implements an AI-powered Video Analytics System using YOLOv11 to detect critical surveillance activities in real-time:

- Explosion
- Road Accidents
- Shooting
- Stealing
- Vandalism

The notebook contains a complete end-to-end workflow, including dataset preparation → YOLO dataset formatting → training → evaluation → inference on real videos.

## Technique Used 
- Deep Learning–based Object Detection
- YOLO11x (You Only Look Once) model
- Frame-level multi-class detection

## System Flow

- Video Input → Frame Extraction (10 FPS) → YOLO Annotation → YOLO11x Training → Evaluation → Real-Time Inference → Crime Detection Output

## Dataset Used
- DCSASS (Dataset for Crime Activity Surveillance Systems)
- Out of which 5 classes are been used: Explosion , Vandalism , Shooting , Stealing & Road Accidents to train the model.






