# Code-for-RDA-YOLO
# RDA-YOLO: Robust Dynamic Adaptive Network for Tiny Insulator Defect Detection

## 📌 Overview
This repository provides the official implementation of **RDA-YOLO**, a robust dynamic adaptive network designed for detecting tiny insulator defects under complex aerial environments.

The proposed method enhances YOLOv8 by introducing:

- **iLSK (Inverted Large Selective Kernel Module)** for adaptive receptive field learning  
- **Dynamic Head (DyHead)** for scale-aware, spatial-aware, and task-aware feature fusion  
- **DA-WIoU Loss** for improved localization performance of small objects  

---

## 🧠 Method Architecture

RDA-YOLO improves detection performance in complex backgrounds and adverse conditions such as haze and long-distance aerial imaging.

Main components:

- Backbone + Neck enhancement with **iLSK**
- Detection head replaced with **Dynamic Head**
- Localization optimized via **DA-WIoU**

---

## 📂 Project Structure
RDA-YOLO/
├── ultralytics/ # Modified YOLOv8 framework
├── configs/ # Model configs
├── scripts/ # Train / val / inference scripts
├── examples/ # Demo images
├── requirements.txt
├── README.md
└── LICENSE
