Animal Behavior Tracking for Neurological Disorder Diagnosis
This repository contains the code and resources for a computer vision-based system to track and analyze animal behaviors (zebrafish and rats) to aid in diagnosing neurological disorders.
The project leverages YOLOv8 for object detection, DeepSORT with a custom ResNet-50 for multi-object tracking, and K-Means clustering for trajectory analysis.The system processes video data, extracts behavioral patterns, and generates visualizations like heatmaps and trajectory plots.

This work was published in IEEE Xplore: https://ieeexplore.ieee.org/document/10783596.

Key Features
Object Detection: Identifies animals in video frames using YOLOv8.
Multi-Object Tracking: Tracks animals across frames using DeepSORT with a custom ResNet-50 for appearance features.
Trajectory Analysis: Extracts and clusters trajectories to identify behavioral patterns.
Visualization: Generates heatmaps, trajectory plots, and annotated videos.

Datasets
The system was trained and tested on:
3D-ZeF20: Zebrafish behavior dataset.
AnimalTrack: Chicken behavior dataset (used for comparison). Note: Due to size constraints, datasets are not included. See Data Access for instructions.

Example Results

YOLO identifies animals in video frames with bounding boxes:
![Rat](https://github.com/user-attachments/assets/0d636430-c6c9-4a78-9c2e-66ad1b415fa6)
![WhatsApp Image 2025-04-21 at 02 40 49_511a286c](https://github.com/user-attachments/assets/70d4f6e4-dd8c-4fbe-ad96-3596ee1b500e)
![YOLO_Only](https://github.com/user-attachments/assets/9a6855ef-5cc8-4743-bb6f-7355fccf863f)

Multi-Object Tracking
![Uploading YOLO+Deepsort.png…]()
![YOLO+Deep](https://github.com/user-attachments/assets/e71d1652-1ab4-43db-a5f5-ae542c40aed5)


