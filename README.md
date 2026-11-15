# Assignment CVPR - Flower Classification Using CNN

## Project Overview
This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images into five flower categories.

## Dataset
The dataset contains 5,000 images across five classes:
- Lilly
- Lotus
- Orchid
- Sunflower
- Tulip

## Model Architecture
A custom CNN was developed using:
- Two convolutional layers
- ReLU activation
- Max pooling
- Two fully connected layers

## Training Configuration
- Image size: 32 × 32
- Batch size: 32
- Optimizer: Adam
- Learning rate: 0.001
- Loss function: CrossEntropyLoss
- Epochs: 10
- Dataset split: 70% Training, 15% Validation, 15% Testing

## Results

| Metric | Result |
|---|---:|
| Training Accuracy | 84.60% |
| Validation Accuracy | 73.20% |
| Test Accuracy | 67.87% |
| Test Loss | 0.8889 |

## Evaluation
The model was evaluated using:
- Precision
- Recall
- F1-score
- Confusion Matrix

## Technologies Used
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Files
- `CNN_23_50297_1.ipynb` – Complete implementation, training, and evaluation.
- `flower_cnn.pth` – Trained CNN model weights.

## Author
Mahamudul Haque
