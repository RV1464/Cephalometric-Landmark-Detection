# Cephalometric Landmark Detection 
This project aims to develop an automatic, accurate, and robust system for cephalometric landmark annotation on 2D high-resolution X-ray images (cephalograms). This addresses the challenges of manual annotation, which is typically tiresome, time-consuming, subjective, and prone to significant intra- and inter-observer variability.

## Project Overview
Cephalometric landmarking is critical for orthodontic and orthognathic treatment planning. By automating this process, the project seeks to enhance the efficiency and precision of cephalometric analysis, thereby providing better support for clinicians in making informed treatment decisions.

## Key Features & Methodology
The approach involves training advanced deep learning models to pinpoint specific anatomical landmarks on cephalometric images:

### Automated Annotation: 
Developed a system to automatically detect and annotate key cephalometric landmarks.
### Deep Learning Models: 
Leveraged state-of-the-art architectures including YOLOv8, ResNet-50, and Inception-v3 for feature extraction and landmark prediction.
### Precision and Robustness: 
Focused on building a solution that delivers high accuracy and consistent performance across diverse cephalograms.
### Dataset Utilization: 
Trained and evaluated models on a dataset of cephalometric X-ray images.

## Technologies Used
#### Programming Language: Python
#### Deep Learning Frameworks: PyTorch (for YOLOv8), TensorFlow/Keras (for ResNet-50, Inception-v3)
#### Image Processing: OpenCV (cv2)
#### Data Handling: Pandas, NumPy
#### Model Evaluation: Mean Radial Error (MRE)

## Performance Evaluation
The model's performance is rigorously evaluated using:

Mean Radial Error (MRE): Quantifies the average Euclidean distance between predicted and ground truth landmark coordinates.
