# 🧠 Animal Behavior Tracking for Neurological Disorder Diagnosis

This repository provides code and resources for a computer vision system designed to **track and analyze animal behavior** (specifically **zebrafish and rats**) to support the **diagnosis of neurological disorders**.

The system leverages:
- **YOLOv8** for real-time object detection
- **DeepSORT** with a **custom ResNet-50** for appearance-based multi-object tracking
- **K-Means clustering** for trajectory pattern analysis

The final output includes **behavioral visualizations**, such as **heatmaps** and **trajectory plots**, extracted from raw video data.

📄 **Published Paper**  
This work was published in **IEEE Xplore**: [Link to Publication](https://ieeexplore.ieee.org/document/10783596)

---

## 🚀 Key Features

- **🟥 Object Detection:** Detects animals (zebrafish and rats) in video frames using YOLOv8.
- **🟦 Multi-Object Tracking:** Tracks multiple animals across frames using DeepSORT with a custom ResNet-50 for appearance features.
- **📈 Trajectory Analysis:** Extracts and clusters trajectories using K-Means to identify behavioral patterns.
- **🖼️ Visualization:** Generates annotated videos, heatmaps, and trajectory plots for behavior analysis.

---

## 📂 Datasets

The system was trained and evaluated on:

- **3D-ZeF20**: Zebrafish behavior dataset.
- **AnimalTrack**: Chicken behavior dataset (used for comparative analysis).
- **Custom Rat Dataset**: Experimental dataset for rat behavior tracking and analysis.

---

## 🎬 Demos

- **YOLOv8 Demo** – [Watch Demo](#) 
- 

https://github.com/user-attachments/assets/af106123-0711-4cb2-a7d0-7b7b5ffc98dd


- **YOLOv8 + DeepSORT Demo** – [Watch Demo](#) *(Replace with actual link)*

---

## 🧪 Example Results

### 🎯 Object Detection  
YOLOv8 identifies and localizes animals in frames:

<p float="left">
  <img src="https://github.com/user-attachments/assets/0d636430-c6c9-4a78-9c2e-66ad1b415fa6" width="250"/>
  <img src="https://github.com/user-attachments/assets/70d4f6e4-dd8c-4fbe-ad96-3596ee1b500e" width="250"/>
  <img src="https://github.com/user-attachments/assets/9a6855ef-5cc8-4743-bb6f-7355fccf863f" width="250"/>
</p>

### 🧍 Multi-Object Tracking  
Combining YOLOv8 with DeepSORT for continuous animal tracking:

<p float="left">
  <img src="https://github.com/user-attachments/assets/0d7915d7-f2ef-4768-8ecb-1bdbe8e8bac3" width="300"/>
  <img src="https://github.com/user-attachments/assets/e71d1652-1ab4-43db-a5f5-ae542c40aed5" width="300"/>
</p>

---

## 📊 Trajectory Analysis & Visualization

- Heatmaps to highlight areas of frequent activity
- Trajectory clustering to detect behavioral patterns

(*Add visualizations or links here if available*)

---

## 🧰 Technologies Used

- **YOLOv8** – Object Detection
- **DeepSORT** – Multi-Object Tracking
- **ResNet-50** – Appearance Feature Extractor
- **OpenCV / Matplotlib / Seaborn** – Visualization Tools
- **Sklearn** – Clustering with K-Means

---

