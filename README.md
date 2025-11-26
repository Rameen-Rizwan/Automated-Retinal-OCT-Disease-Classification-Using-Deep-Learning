# Automated Retinal OCT Disease Classification Using Deep Learning

## Overview
This project applies deep learning for automatic classification of retinal OCT images into four categories: CNV, DME, Drusen, and Normal. It supports early detection of retinal diseases through AI-based medical image analysis.

## Dataset
- Retinal OCT image dataset
- Contains four classes: CNV, DME, Drusen, Normal
- Images resized and preprocessed before model training

## Model
- Convolutional Neural Network (CNN)
- Implemented using TensorFlow/Keras
- Achieves high classification accuracy

## Features
- Automated disease detection
- Training with data augmentation
- Visualization of model performance
- Can aid clinical diagnostic workflows

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter / Google Colab

## Evaluation Metrics
- Accuracy
- Loss
- Confusion matrix
- Classification report

## Usage
```python
model.predict(your_oct_image)
