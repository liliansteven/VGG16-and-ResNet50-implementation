# Image Classification using VGG-16 and ResNet-50 Architectures
## Overview
This repository demonstrates effective methods for image classification using Four models were considered: `VGG16 from Scratch`, `Pre-trained VGG16`, `ResNet-50 from Scratch`, and `Fine-tuned Pre-trained ResNet-50` on two different datasets **(CIFAR10 and Flowers)**. The primary focus is on achieving accurate classification results and understanding the impact of using pre-trained models.

## Key Features
### 1. Dataset 
1. **CIFAR10 dataset**: 60000 32x32 colour images in 10 classes.
2. **Flowers dataset**: Collection of flower images.

### 2. Models

1. VGG16 from Scratch:
    - Custom VGG16 with batch normalization.
    - CIFAR-10: Improved accuracy, Flowers: Slight decrease.

2. Pre-trained VGG16:
    - Utilized a pre-trained VGG16 with ImageNet weights.
    - Significant accuracy boost on both datasets.

3. ResNet-50 from Scratch:
    - Custom ResNet-50 architecture.
    - Decent accuracy, slightly below pre-trained VGG16.

4. Fine-tuned Pre-trained ResNet-50:
    - Pre-trained ResNet-50 fine-tuned on each dataset.
    - Superior performance on CIFAR-10, slightly lower on Flowers.

### 3. Evaluation Metrics and Confusion Matrices
- Generate confusion matrices for testing samples on both custom and pre-trained models. 
- Calculate precision, recall, and F1 score to assess model performance.

### 4. Results Analysis
- Explores and comments on the results obtained from custom and pre-trained models.
- Analyzes the impact of transfer learning on classification accuracy and training efficiency.

