# Chest X-Ray Anomaly Detection using Deep Learning

## Overview

This project is an AI-powered medical imaging system designed to automatically analyze chest X-ray images and classify them into:

- COVID-19
- Non-COVID Infection
- Normal

The system leverages multiple state-of-the-art Convolutional Neural Network (CNN) architectures and combines them using an ensemble learning approach to improve diagnostic accuracy and robustness.

To enhance model transparency and trustworthiness, Grad-CAM visualizations are generated to highlight the regions of the X-ray that influenced the model's decision.

## Features

- Multi-class Chest X-Ray Classification
- Transfer Learning using pretrained CNN models
- Ensemble Learning for improved performance
- Grad-CAM Explainability
- Disease Region Localization
- Automated Medical Image Analysis Pipeline
- Performance Benchmarking Across Multiple Architectures

## Deep Learning Models Evaluated

- EfficientNet
- ResNet
- DenseNet
- VGG
- Inception-ResNet

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Scikit-Learn

## Methodology

1. Data Collection and Preprocessing
2. Image Augmentation
3. Transfer Learning with Pretrained CNN Models
4. Model Training and Evaluation
5. Ensemble Prediction Generation
6. Grad-CAM Visualization
7. Disease Region Segmentation and Analysis

## Results

- High classification accuracy across multiple chest X-ray categories
- Improved robustness through weighted ensemble learning
- Explainable AI outputs using Grad-CAM heatmaps
- Clinically meaningful localization of abnormal regions
