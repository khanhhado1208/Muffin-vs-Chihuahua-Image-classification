# Muffin-vs-Chihuahua-Image-classification

## Features

### Custom dataset loading and preprocessing
- CNN with:
  - Data Augmentation (random flip, random rotation)
  - Two Conv2D + MaxPooling + BatchNorm layers
  - Dense layers with Dropout
### Binary classification with `sigmoid` output
### Evaluation using:
  - Accuracy
  - Confusion Matrix
  - ROC Curve + AUC
  - Threshold tuning for optimal performance

## Model Architecture

Input → Data Augmentation → Conv2D(16) → MaxPool → BatchNorm → 
Conv2D(24) → MaxPool → BatchNorm → Flatten → Dense(8) → Dropout → 
Dense(1, sigmoid)

## Results
- Final Validation Accuracy: ~78.89%

- Best ROC AUC: ~0.91

- Optimized classification threshold: 0.2345

## Visualizations
- Confusion Matrix (default + best threshold)

![image](https://github.com/user-attachments/assets/39cbb185-b933-4d6e-8cde-51680f311f68)

- ROC Curve

![image](https://github.com/user-attachments/assets/30019519-3f72-4358-a562-6398b0d85643)

