# Fashion-MNIST-Classification-using-ANN-and-CNN
Deep learning based Fashion-MNIST image classification project using ANN, Basic CNN, and Deeper CNN architectures with TensorFlow/Keras. Includes data preprocessing, EarlyStopping, ModelCheckpoint, accuracy visualization, and model performance comparison.

# 👕 Fashion-MNIST Classification using ANN & CNN

A deep learning project for Fashion-MNIST image classification using Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN) with TensorFlow/Keras.

# 🚀 Project Overview

This project focuses on classifying grayscale fashion product images from the Fashion-MNIST dataset using multiple deep learning architectures.

The project includes:

- Artificial Neural Network (ANN)
- Basic Convolutional Neural Network (CNN)
- Deeper CNN Architecture
- Performance comparison between ANN and CNN
- Training optimization using EarlyStopping and ModelCheckpoint

# 📂 Dataset

The project uses the Fashion-MNIST dataset provided by Zalando Research.

### Dataset Information

- Total Images: 70,000
- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28×28 pixels
- Classes: 10


# 🏷️ Fashion Categories

| Label | Class |
|---|---|
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |


# 🧠 Models Implemented

## 1️⃣ Artificial Neural Network (ANN)

### Architecture
- Flatten Layer
- Dense Layer (128 neurons, ReLU)
- Dense Layer (64 neurons, ReLU)
- Output Layer (Softmax)

### Highlights
- Simple baseline model
- Faster training
- Lower computational cost


## 2️⃣ Basic CNN

### Architecture
- Conv2D
- MaxPooling2D
- Conv2D
- MaxPooling2D
- Flatten
- Dense
- Softmax Output

### Highlights
- Better feature extraction
- Improved image understanding
- Higher accuracy than ANN


## 3️⃣ Deeper CNN

### Highlights
- More convolution layers
- Improved feature learning
- Better generalization performance
- Higher classification accuracy


# ⚙️ Features

- Data preprocessing
- Normalization
- One-hot encoding
- ANN implementation
- CNN implementation
- Deeper CNN architecture
- EarlyStopping callback
- ModelCheckpoint callback
- Accuracy visualization
- Prediction visualization

# 🛑 EarlyStopping

EarlyStopping is used to stop model training when validation loss stops improving.

### Benefits
- Prevents overfitting
- Reduces unnecessary training
- Restores best model weights


