# CNN Fashion-MNIST Image Classification

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images from the Fashion-MNIST dataset.

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## Model Architecture
- Conv2D (32 filters, 3x3)
- MaxPooling2D
- Flatten Layer
- Dense Layer (64 neurons)
- Output Layer (Softmax)

## Dataset
Fashion-MNIST dataset containing 70,000 grayscale images of clothing items across 10 classes.

## Results
The model achieved approximately **90% test accuracy**.

## Example Prediction
The model predicts the class of a clothing image and compares it with the actual label.

## How to Run

```bash
pip install tensorflow matplotlib numpy
python cnn_fashion_mnist.py
