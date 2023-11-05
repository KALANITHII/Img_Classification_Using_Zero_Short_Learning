# Zero-Shot Learning for Image Classification with CIFAR-100 Dataset

This repository contains an implementation of Zero-Shot Learning (ZSL) for image classification using the CIFAR-100 dataset. In this approach, we utilize a fast vectorizer for feature extraction, the VGG19 model for training, and cosine similarity for zero-shot learning to classify images for classes that were not seen during the training phase.

## Prerequisites

Before getting started, make sure you have the following prerequisites installed on your system:

- Python 3
- TensorFlow or Keras
- Scikit-learn
- Other required libraries (e.g., numpy, matplotlib, etc.)

You can install most of these packages using pip:

```bash
pip install tensorflow scikit-learn numpy matplotlib
