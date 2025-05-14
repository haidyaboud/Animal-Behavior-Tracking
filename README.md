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

