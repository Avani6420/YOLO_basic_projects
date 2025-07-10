YOLOv11 Projects on Roboflow Datasets
This repository contains a collection of projects built using YOLOv11 for various computer vision tasks such as object detection, image classification, segmentation, and object tracking. 
The models are trained and tested on multiple datasets sourced from Roboflow.

1. YOLO11_Overview
  Comprehensive demonstrations of:
    Object Detection
    Instance Segmentation
    Image Classification
  Applied to both images and videos, showcasing the versatility of YOLOv11.

2. Custom_Data_Training
  Custom training on a PPE (Personal Protective Equipment) dataset to detect:
    Safety Helmets
    Face Masks
    Safety Jackets
    Safety Shoes
    And other protective gear
  Use case: Ensuring compliance with safety protocols at construction or industrial sites.

3. Instance_Segmentation
  Brain tumor detection using YOLOv11 with segmentation capabilities, highlighting:
    Region-wise segmentation of tumors
    Enhanced visualization for medical image analysis
    Dataset includes annotated brain MRI images.

4. Img_Classification
  Image classification on the Chicken Fecal Dataset to determine:
    Healthy samples
    Coccidiosis-infected samples
  Aimed at assisting in early disease detection in poultry.

5. Helmet_Detection
  Helmet detection system to classify whether:
    A person is wearing a helmet
    Or not wearing a helmet
  Real-world application: Smart surveillance at construction zones and traffic monitoring.

6. Object_Tracking_with_ByteTrack_and_BOT-SORT
  Multi-object tracking using:
    ByteTrack
    BOT-SORT
  Features:
    Person detection from video
    Consistent ID assignment for tracking across frames
  Real-time tracking demonstration

Dataset Source
  All datasets are imported and managed using Roboflow, allowing fast preprocessing, annotation, and version control.

Tools & Frameworks
  YOLOv11 (Ultralytics)
  Roboflow
  OpenCV
  ByteTrack / BOT-SORT
  Python
