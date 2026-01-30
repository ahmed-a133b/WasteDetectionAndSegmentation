# Waste Detection and Segmentation

This project applies deep learning for environmental sustainability by combining object detection and segmentation to identify and classify recyclable and non-recyclable materials.

## Overview

The project implements two complementary approaches:
- **Object Detection**: YOLOv8 (small and medium variants) for detecting waste objects
- **Semantic Segmentation**: U-Net for pixel-level segmentation of waste materials

## Repository Structure

- `yolov8s.ipynb` - YOLOv8 small model
- `yolov8m.ipynb` - YOLOv8 medium model
- `unet.ipynb` - Custom U-Net segmentation model
- `Report.pdf` - Project report and findings

## Models

### YOLOv8
Object detection for identifying waste items in images.

### U-Net
Segmentation for precise pixel-level classification.

## Usage

Each notebook contains training and evaluation of the model.

## Requirements

- Python 3.11+
- Jupyter Notebook
- PyTorch
- Ultralytics (for YOLOv8)
- Standard deep learning libraries
