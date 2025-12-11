Lab 09: Object Detection with Pascal VOC 2007 (SSD MobileNet V2)
📌 Overview

In this lab, I learned how to perform object detection, which goes beyond classification by identifying what is in an image and where it is located using bounding boxes.
We used the Pascal VOC 2007 dataset and a pre-trained SSD MobileNet V2 model from TensorFlow Hub.


Lab9VOC2007__Dataset_student_No…

🗂 What I Did

Loaded a small subset of the VOC 2007 dataset for efficiency.

Explored images with ground truth bounding boxes.

Loaded the SSD MobileNet V2 model for real-time object detection.

Visualized predictions with bounding boxes and labels.

Compared ground truth vs. model predictions on sample images.

Implemented IoU (Intersection over Union) to evaluate bounding box accuracy.

Tested precision on a validation subset.


Lab9VOC2007__Dataset_student_No…

📚 What I Learned

Object detection ≠ classification — detection predicts both labels and box coordinates.

SSD MobileNet V2 is fast and lightweight, making it suitable for low-resource environments.

IoU helps measure how close predicted boxes are to the ground truth.

Using only 10% of the dataset leads to limited accuracy, as shown by low precision.

Visualization helps understand which object types the model detects well and where it struggles.


Lab9VOC2007__Dataset_student_No…

🧠 Key Takeaways

Pre-trained models allow object detection without long training times.

Dataset quality and size heavily impact model performance.

Lighting, occlusion, and complex scenes can reduce detection accuracy.

Higher IoU thresholds make evaluation stricter and reduce true positives.

📂 Files

Lab9VOC2007__Object_Detection_transfer_learning.ipynb – 
