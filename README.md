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
