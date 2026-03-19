# Sugar Adulteration Detection using Ensemble Learning

## Overview
This project focuses on detecting sugar adulteration using advanced **deep learning ensemble techniques**. It combines multiple state-of-the-art CNN architectures and incorporates uncertainty estimation and interpretability methods, making it suitable for **research and thesis-level work**.

---

## Features

- Multiple deep learning models:
  - ResNet50  
  - DenseNet121  
  - ConvNeXt-Tiny  

- Ensemble Learning (Soft Voting)

- Test Time Augmentation (TTA)

- Uncertainty Estimation:
  - Monte Carlo Dropout  

- Out-of-Distribution Detection:
  - Mahalanobis Distance  

- Model Explainability:
  - Grad-CAM Heatmaps  

- Performance Evaluation:
  - Accuracy, Precision, Recall, F1-score  
  - Confusion Matrix  
  - Visualization tools  

---

## Model Architecture

This project uses an **ensemble approach**, combining predictions from multiple pretrained CNN models. The final prediction is obtained using **soft voting**, which improves robustness and accuracy compared to individual models.

---
