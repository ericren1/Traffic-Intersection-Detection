# YOLOv5n vs YOLOv8n Traffic Vehicle Detection

This repository contains a comparative study of **YOLOv5n** and **YOLOv8n** for real time vehicle detection and counting in traffic intersection environments.  

The goal is to evaluate whether YOLOv8’s architectural improvements translate into practical real world performance improvements that are significant enough to upgrade from the current industry standard model.

## 🚦 Project Overview

Traffic intersections are dynamic environments with vehicles, cyclists, and pedestrians moving simultaneously.  
Accurate real time vehicle detection is essential for:
- Congestion monitoring  
- Adaptive traffic signal control  
- Road safety analysis  
- Automated traffic management systems  

YOLO based object detectors are widely used due to their balance between **speed** and **accuracy**.  
This project compares two model variants:
- **YOLOv5n**  
- **YOLOv8n** 

We analyze performance using:

- **Frames Per Second (FPS)**  
- **Total Vehicle Detections**  
- **Per Frame Detection Trends**  
- **Processing Time per Model**

All models are tested on the same real-world intersection footage using pretrained COCO weights.


## 👥 Contributors
- **Eric Ren**
- **Tanin Tafader**
- **Harshil Suthar**
