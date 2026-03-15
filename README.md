# AI-Based Casting Defect Detection

This repository contains the implementation developed for my Master's thesis:

**"Automated Casting Defect Detection Using Deep Learning in Industry 4.0"**

The goal of this project is to build an AI-based quality inspection system that detects casting defects in submersible pump impellers using deep learning models.

## Overview

Manual inspection in manufacturing is time-consuming and prone to human error.  
This project proposes an automated defect detection system using computer vision and deep learning to classify casting products into:

- Defective
- Non-Defective

## Models Implemented

The following deep learning architectures were evaluated:

- MobileNetV2  
- ResNet50  
- Xception  
- EfficientNet-B0  
- DeiT-Small (Vision Transformer)

Models were compared using metrics such as **accuracy, precision, recall, and F1-score**.

## Dataset

The models were trained using the **Casting Product Image Dataset** available on Kaggle.

Dataset details:
- Total images: **7,348**
- Image type: **Grayscale**
- Resolution: **300×300**
- Classes: **Defective / Non-Defective**

Dataset link:  
https://www.kaggle.com/datasets/ravirajsinh45/real-life-industrial-dataset-of-casting-product

## Repository

GitHub:  
https://github.com/NimeshKotian/casting-defect-detection
