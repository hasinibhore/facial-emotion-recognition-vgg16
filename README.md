# Facial Emotion Recognition using Deep Learning (ResNet50)

## Overview
A deep learning model to recognize 7 human facial emotions
from images using Transfer Learning with ResNet50.

## Emotions Detected
Angry | Disgust | Fear | Happy | Neutral | Sad | Surprise

## Dataset
Face Expression Recognition Dataset (CK+)
- Small, clean, well labeled dataset
- 7 emotion classes
- Source: Kaggle

## Model Architecture
- Base Model: ResNet (pretrained on ImageNet)
- Frozen base layers for feature extraction
- Custom classification head added
- Dropout layers to prevent overfitting

## Results
- Validation Accuracy: [add after training finishes]%
- Loss: [add after training finishes]

## Tech Stack
Python | TensorFlow | Keras | ResNet50 | Matplotlib | Seaborn

## How to Run
1. Open notebook in Google Colab
2. Download Face Expression dataset from Kaggle
3. Run all cells in order

## Key Concepts Used
- Transfer Learning
- Data Augmentation
- EarlyStopping and ReduceLROnPlateau callbacks
- Confusion Matrix Analysis
