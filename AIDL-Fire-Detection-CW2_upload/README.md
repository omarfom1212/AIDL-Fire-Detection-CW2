# AIDL-Fire-Detection-CW2
Fire vs No-Fire Image Classification using CNN and Transfer Learning

## Overview
This project implements a deep learning solution for binary fire detection from images.
A custom CNN is compared against a transfer learning model (MobileNetV2).

## Dataset
- Total images: 1,192 (balanced)
- Classes: fire, no_fire
- Train: 1,092 images (546 per class)
- Test: 100 images (50 per class)
> Images are not uploaded due to size limitations. See `dataset/README.txt`.

## Methods
- Proposed CNN: Conv + Pool blocks with Dropout and EarlyStopping.
- Transfer Learning: MobileNetV2 pretrained on ImageNet with frozen base and custom classifier head.

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
