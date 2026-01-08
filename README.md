# AIDL-Fire-Detection-CW2
Fire vs No-Fire Image Classification using CNN and Transfer Learning

## Overview
This repository contains the final implementation for AIDL CW2.
A custom CNN is compared with a transfer learning model (MobileNetV2).

## Dataset
- Total images: 1,192 (balanced)
- Classes: fire, no_fire
- Train: 1,092 images (546 per class)
- Test: 100 images (50 per class)

> Images are not included due to size limitations. See `dataset/README.txt`.

## Results (Test Set)
- Proposed CNN: Accuracy = 0.99, F1-score = 0.99
- Transfer Learning (MobileNetV2): Accuracy = 1.00, F1-score = 1.00

## How to Run
```bash
pip install -r requirements.txt
