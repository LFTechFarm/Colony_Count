# 🧫 Colony Count Inference with YOLOv8

## 📌 Purpose

This project demonstrates the use of YOLOv8 for automated detection and counting of bacterial colonies on petri dish images.
The goal is to provide a fast, accurate, and reproducible alternative to manual counting, which is often slow and prone to error.

<img width="1481" height="658" alt="output3" src="https://github.com/user-attachments/assets/eedab8b4-9386-4ffa-a386-82717b6ce74e" />

## 🖼️ How It Works

Input: Petri dish image
Model: Pretrained YOLOv8 detector

Output:
Bounding boxes highlighting detected colonies
Colony count displayed on the result image

This inference workflow helps visualize how object detection can be applied in microbiology and related fields.

## 🚀 Usage

Place your input images in the images/ folder.
Run inference with the YOLOv8 model (pretrained weights).

View the results in the runs/detect/predict/ folder — colony counts are displayed directly on the images.

## 🔜 Next Steps

The current implementation performs well for medium and large colonies, but struggles with small & dense colony detection.
Planned improvements include:  
Adjusting YOLOv8 parameters for small objects

Increase the dataset with small colony





