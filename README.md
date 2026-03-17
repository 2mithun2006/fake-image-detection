# Fake Screenshot / Edited Image Detection

## Problem Statement
Detecting manipulated or tampered digital images using 
Machine Learning (ELA + CNN)

## Results
- Accuracy: 86%
- AUC-ROC: 0.96
- Tampered Detection: 99.83% confidence
- Authentic Detection: 100% confidence

## Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- Pillow (PIL)
- Scikit-learn
- Google Colab (T4 GPU)

## Technique
**ELA (Error Level Analysis)** + **CNN (Convolutional Neural Network)**

## Dataset
CASIA2 Image Tampering Dataset
- 7,491 Authentic images
- 5,123 Tampered images

## Model Architecture
- 4 Convolutional Blocks (32, 64, 128, 256 filters)
- Batch Normalization + MaxPooling
- Dense layers with Dropout (50%, 30%)
- Binary Classification (Sigmoid output)

## Wow Features
1. Heatmap showing edited regions
2. Image forensic metadata analysis
3. Compression artifacts comparison
4. Full forensic report

## How To Run
1. Open fake_image_detection.ipynb in Google Colab
2. Run all cells in order
3. Dataset downloads automatically via Kaggle API

## Event
CADES Hackathon — SRM Institute of Science and Technology