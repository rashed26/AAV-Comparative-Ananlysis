# Comparative Study: Supervised and Semi-Supervised AAV Image Classification

This repository contains the implementation and evaluation of supervised and semi-supervised learning approaches for multi-class image classification. Our goal is to compare the performance of traditional machine learning classifiers trained on deep CNN-based features with modern semi-supervised methods that utilize both labeled and unlabeled data.

---

## Overview

We evaluated two learning paradigms:

### 1. Supervised Learning
We used five widely adopted convolutional neural networks (CNNs) as feature extractors:
- ResNet18
- ResNet50
- VGG16
- MobileNetV2
- InceptionV3

From these features, we trained classical machine learning classifiers:
- Support Vector Machine (SVM)
- Random Forest (RF)
- K-Nearest Neighbors (KNN)

### 2. Semi-Supervised Learning
We implemented two recent and popular semi-supervised methods:
- **FixMatch**: Combines consistency regularization with pseudo-labeling and strong data augmentation.
- **MixMatch**: Blends labeled and unlabeled data using a mixup strategy and entropy minimization.

All experiments were conducted under the same dataset and evaluation protocol for fair comparison.



