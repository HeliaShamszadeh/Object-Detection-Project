# Object Detection Project using YOLO

This project demonstrates how to build a basic object detection system using the **YOLO (You Only Look Once)** model. The goal of the project was to detect a specific object—in this case, a **book**—within videos using deep learning and computer vision techniques.

---

## Project Objective

- Detect a **book** in input video streams using a YOLO-based object detection pipeline.
- Train the model on a custom dataset created with labeled bounding boxes.
- Evaluate and visualize detection performance frame-by-frame.

---

## Tools & Technologies

- **Language:** Python
- **Frameworks & Libraries:**  
  `OpenCV`, `YOLOv5`, `PyTorch`, `LabelImg`, `NumPy`
- **Model:** YOLOv5 (pre-trained weights fine-tuned for custom dataset)
- **Annotation Tool:** LabelImg

---

## Workflow Overview

1. **Dataset Preparation**
   - Collected video frames containing books
   - Annotated frames using `LabelImg` to generate YOLO format labels

2. **Model Training**
   - Fine-tuned a YOLOv5 model on the custom dataset
   - Adjusted configuration for number of classes (1 class: "book")

3. **Detection & Evaluation**
   - Loaded trained model
   - Performed inference on new video frames
   - Drew bounding boxes around detected books

4. **Visualization**
   - Real-time visualization of detection results using OpenCV
   - Optionally saved detection outputs as video files

---
  
## Sample Results
![image](https://github.com/user-attachments/assets/4adbfa32-7ccb-4738-b446-539ad5b02673)

![image](https://github.com/user-attachments/assets/c6a77fa9-1d0d-413b-96b3-5ba12d9cbb42)

![image](https://github.com/user-attachments/assets/1f2a106c-cc51-42c5-8689-cbe86f0d7762)


