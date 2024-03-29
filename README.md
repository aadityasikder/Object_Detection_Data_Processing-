# Object Detection using Raspberry Pi and TinyML Models

This repository contains code and resources for performing object detection using TinyML models like TensorFlow Lite and PyTorch Nano on a Raspberry Pi. It also includes tools for gathering data on metrics such as mean Average Precision (mAP) value, temperature, etc. Additionally, there are scripts for preparing image data from various sources, cleaning them, and combining them into a single dataset of required classes, all within Jupyter Notebooks.

## Contents

1. **Training YOLOv5 Models**: The `first_yolov5.ipynb` Jupyter Notebook is used to train YOLOv5 TensorFlow and PyTorch models.
2. **Conversion to TensorFlow Lite**: The `Yolov5 (1).ipynb` Jupyter Notebook file is used to convert TensorFlow models to TensorFlow Lite files.
3. **Model Performance Data**: Results of testing all models on Raspberry Pi 400 are provided in the `yolov5-model-performance-data.xlsx` file.
4. **Data Preparation**: The `untitled.ipynb` Jupyter Notebook file contains code to prepare image data from various sources, combining them, and editing classes as required.

## Requirements

- Raspberry Pi 400 or similar device.
- TensorFlow, PyTorch, and other dependencies as specified in the Jupyter Notebooks.
- Access to various image datasets for training and testing.

## Contributors

- [Aaditya Sikder](https://github.com/aadityasikder)


