FridgeVision: Smart Grocery Detection Using YOLO
📌 Overview

This project uses YOLOv8 to automatically detect grocery items inside a refrigerator. The goal is to build a system that can track inventory, reduce food waste, and move toward smart-fridge automation.

🧠 Problem Statement

Manually checking fridge items is slow and easy to mess up. This project aims to automate the process using computer vision, allowing real-time detection of groceries from images.


FridgeVision_Complete_Presentat…

📂 Dataset

GroceryStoreDataset (GitHub)

Thousands of product images

81 different classes

Includes train/val/test splits

We converted the dataset into YOLO format for training

---

FridgeVision_Complete_Presentat…

🛠 What We Did

Cloned the dataset and parsed classes.csv

Converted images + labels into proper YOLO structure

Fixed formatting issues inside label files

Auto-generated a dataset config file (grocery_data.yaml)

Trained YOLOv8 using the ultralytics library

Evaluated detection results on fridge images

---

FridgeVision_Complete_Presentat…

🤖 Model Details

Model: YOLOv8

Components: Backbone, Neck, Head

Outputs: Bounding boxes, class names, confidence

Learned all 81 grocery categories

---


FridgeVision_Complete_Presentat…

🎯 System Workflow

User uploads a fridge or grocery image

YOLO performs inference

Items appear with bounding boxes + labels

System logs them for inventory tracking

---


FridgeVision_Complete_Presentat…

⚠️ Challenges

Lighting and background differences in images

Class imbalance (some items appear way more than others)

Bounding boxes in the dataset were low-quality, requiring adjustments

Limited computing power in Google Colab

---


FridgeVision_Complete_Presentat…

🚀 Future Improvements

Add real bounding box annotations instead of full-image boxes

Deploy as a mobile app or fridge camera system

Add data augmentation to improve accuracy

Integrate OCR to detect expiration dates

---

FridgeVision_Complete_Presentatation

📁 Files

FridgeVision_Complete_Presentation.pptx – Final project slides
