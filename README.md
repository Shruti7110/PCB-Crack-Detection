# PCB-Crack-Detection

## 🔍 Problem Statement
Manual inspection of PCBs is time-consuming and error-prone. This project automates defect detection to ensure the faulty PCB are being detected at every stage to rework on the PCB. The goal is to aid in real-time quality assurance during PCB manufacturing.

## 🚀 Approach
Utilize a pre-trained YOLOv12 model and fine-tune it on a custom dataset of PCB images from Roboflow.​ \
The Model should be able to predict PCB with broken circuits, component burn-down, damages, less or more tin, missing parts or component shifting.

## ⚙️  Features
Object detection using YOLOv12 \
Custom training on PCB defect dataset \
mAP (mean Average Precision) evaluation \
Inference with bounding boxes and labels

## Disclairmer 
Feel free to use the best.pt file to directly use the model for your application.
