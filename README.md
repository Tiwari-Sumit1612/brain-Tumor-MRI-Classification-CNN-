# Brain Tumor Classification using ANN

## Overview
This project implements a Convolutional Neural Network (CNN) for multi-class classification of brain tumors using MRI images. The model is designed to classify images into different tumor categories with high accuracy and improved generalization.

## Dataset
The dataset consists of brain MRI images classified into:
- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor
- No Tumor

## Methodology

### Data Preprocessing
- Resized images to a fixed input size
- Normalized pixel values
- Split data into training, validation, and test sets

### Data Augmentation
- Rotation
- Flipping
- Zooming
- Random transformations to improve generalization

### Model Architecture
- 7-layer Convolutional Neural Network
- Convolutional + MaxPooling layers for feature extraction
- Fully connected dense layers for classification
- Softmax activation for multi-class output

### Training
- Optimizer: Adam
- Loss Function: Categorical Cross-Entropy
- Evaluation Metric: Accuracy

## Results
- Achieved 95% test accuracy
- Reduced validation loss significantly during training
- Improved model generalization using augmentation

## Overfitting Prevention
- Data augmentation
- Validation monitoring
- Regularization techniques (Dropout / Early Stopping if applied)

## Requirements
- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV

## How to Run
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
