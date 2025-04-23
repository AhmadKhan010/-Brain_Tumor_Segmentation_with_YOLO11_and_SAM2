# Brain Tumor Segmentation with YOLO 11 and SAM

This repository contains a Jupyter notebook (Arch.ipynb) that implements brain tumor segmentation using the YOLO 11 model for object detection and the Segment Anything Model (SAM2) for precise instance segmentation. The project is part of the AI/ML internship offered by ARCH Technologies.

# Project Overview

The notebook demonstrates the following steps:

1. Environment Setup: Installs required libraries (ultralytics for YOLO 11 and segment-anything for SAM2).

2. Model Training: Trains a YOLO 11 Nano (yolo11n.pt) model on a brain tumor dataset to detect tumors (classes: glioma, meningioma, no_tumor).

3. Inference with YOLO 11: Uses the trained YOLO model to detect tumors in test images and outputs bounding boxes.

4. Segmentation with SAM2: Applies the SAM2 model to refine the YOLO detections into precise segmentation masks.

5. Results Visualization: Saves the detection and segmentation results for analysis.

The notebook is designed to run on Google Colab, leveraging its GPU capabilities for faster training and inference.

# Repository Contents

Arch.ipynb: The Jupyter notebook containing all the code for training, inference, and segmentation.

# Prerequisites

To run the notebook, you need the following:

1. Google Colab: The notebook is configured to run on Google Colab with GPU support.

2. Dataset: A brain tumor dataset with a structure compatible with Ultralytics YOLO (e.g., images and a data.yaml file). The notebook assumes the dataset is located at /content/sample_data/TumorData/.

3. Internet Access: To download model weights (yolo11n.pt and sam2_b.pt) and required libraries.

# Acknowledgments

This project follows the tutorial YOLO11 and SAM2 for Custom Instance Segmentation by Code With Arohi Hindi.

The ultralytics library is used for YOLO 11 implementation.

The segment-anything library is used for SAM2 implementation.

# Contact

For questions or issues, please open an issue in this repository or contact me at the email ahamdkhanmarwat8@gmail.com.
