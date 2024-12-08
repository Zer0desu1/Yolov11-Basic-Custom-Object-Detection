# Yolov11-Basic-Custom-Object-Detection
##Custom object detection using yolov11



This guide walks you through setting up a custom object detection model using **YOLOv5**. The steps cover installation, labeling your dataset, training the model, and using the trained model for predictions.

## Requirements

Before we start, ensure you have the following installed:

- Python (>= 3.7)
- **PyTorch**: Install the appropriate version for your system.  
  [PyTorch Installation Guide](https://pytorch.org/get-started/locally/)
- **YOLOv5** by Ultralytics
- **Label Studio** for dataset labeling

## Step 1: Install Ultralytics YOLOv5

Install the `ultralytics` package via pip:

```bash
pip install ultralytics
