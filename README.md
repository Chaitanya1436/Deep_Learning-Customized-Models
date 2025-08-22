# Deep Learning Projects: Customized CNN & GAN with ReLU + One-Hot Encoding  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-1.12+-EE4C2C?logo=pytorch)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.9+-FF6F00?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-2.9+-D00000?logo=keras)
![Accuracy](https://img.shields.io/badge/CNN-83%25-green)
![Accuracy](https://img.shields.io/badge/GAN-89%25-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 About  
This repository contains two deep learning projects developed as part of a research-driven side hustle under academic guidance.  
- **Project 1:** Customized CNN Model trained on CIFAR-10.  
- **Project 2:** GAN-inspired CNN Model with ReLU Activation & One-Hot Encoding trained on MNIST.  

Both models were designed, implemented, and fine-tuned to achieve competitive accuracy on benchmark datasets.  

---

## 🔬 Project 1: Customized CNN Model (CIFAR-10)  

### Overview  
A **Convolutional Neural Network (CNN)** architecture built from scratch and progressively enhanced with:  
- Squeeze-and-Excitation (SE) blocks for channel-wise attention.  
- A variant using **ResNet18 backbone + SEBlock** for feature-rich representation.  

### Dataset  
- **CIFAR-10**: 60,000 images (32×32×3), 10 classes.  
- Data augmentation applied: random cropping, horizontal flipping, normalization.  

### Key Features  
- PyTorch-based implementation.  
- Attention mechanism integration.  
- Early stopping for robust training.  
- Achieved **~83% test accuracy**.  

### Usage  
# Install dependencies
pip install torch torchvision

# Run the notebook
jupyter notebook Customized_CNN_Model.ipynb

##🔬 Project 2: GAN Model with ReLU & One-Hot Encoding (MNIST)

###Overview
A CNN-inspired deep model tested with GAN-related principles like ReLU activations, One-Hot encoding, and enhanced regularization.

###Dataset
MNIST: 70,000 grayscale handwritten digits (28×28).

###Preprocessing steps:
-Normalization
-Reshaping
-Categorical one-hot encoding

###Key Features
Implemented in Keras/TensorFlow.
Convolutional layers with BatchNormalization + Dropout.
Evaluated using Precision, Recall, and Accuracy.
EarlyStopping to mitigate overfitting.
Achieved ~89% test accuracy.

Usage
# Install dependencies
pip install tensorflow keras scikit-learn

# Run the notebook
jupyter notebook GAN_Model_With_RELU_Activation_&_OneHotEncoding.ipynb
