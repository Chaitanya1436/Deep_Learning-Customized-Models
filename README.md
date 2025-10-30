# Deep Learning Projects: Customized CNN & GAN with ReLU + One-Hot Encoding  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python) ![PyTorch](https://img.shields.io/badge/PyTorch-1.12+-EE4C2C?logo=pytorch) ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.9+-FF6F00?logo=tensorflow) ![Keras](https://img.shields.io/badge/Keras-2.9+-D00000?logo=keras) ![Accuracy](https://img.shields.io/badge/CNN-83%25-green) ![Accuracy](https://img.shields.io/badge/GAN-89%25-brightgreen) ![License](https://img.shields.io/badge/License-MIT-yellow)
 

---

## 📌 About  

This repository contains two deep learning projects developed under academic guidance:

## 1. **Customized CNN Model** trained on CIFAR-10  
## 2. **GAN-inspired CNN Model** with ReLU activation & One-Hot Encoding trained on MNIST  

Both models are designed, implemented, and fine-tuned for competitive accuracy on benchmark datasets.

---

## 🔬 Project 1: Customized CNN Model (CIFAR-10)  

**Overview:** CNN built from scratch with:  
- Squeeze-and-Excitation (SE) blocks  
- ResNet18 backbone + SEBlock variant  

**Dataset:** CIFAR-10 (60,000 images, 10 classes) with augmentation  

**Key Features:**  
- PyTorch implementation  
- Early stopping  
- ~93% test accuracy  

---

## 🔬 Project 2: GAN Model with ReLU & One-Hot Encoding (MNIST)  

**Overview:** CNN-inspired GAN model with:  
- ReLU activations  
- One-Hot Encoding  
- BatchNormalization + Dropout  

##**Dataset:** MNIST (70,000 grayscale digits)  

**Key Features:**  
- TensorFlow/Keras implementation  
- EarlyStopping  
- ~89% test accuracy  

---

## 🛠️ Tech Stack  

- Python 3.8+  
- PyTorch 1.12+  
- TensorFlow 2.9+  
- Keras 2.9+  
- Scikit-learn  

---

## 🚀 Usage  

### Project 1: Customized CNN
Install PyTorch:
```bash
pip install torch torchvision
```

Run CNN notebook:
```
jupyter notebook Customized_CNN_Model.ipynb
```
##Project 2: GAN Model

Install TensorFlow, Keras, Scikit-learn:
```
pip install tensorflow keras scikit-learn
```

Run GAN notebook:
```
jupyter notebook GAN_Model_With_RELU_Activation_&_OneHotEncoding.ipynb
```


## 📈 Results

Model performance on different datasets
CNN Model: CIFAR-10
Test Accuracy: ~93%
GAN Model: MNIST
Test Accuracy: ~89%

## 🔮 Future Improvements
 - Try advanced GANs like DCGAN, WGAN
 - Add learning rate schedulers & advanced optimizers
 - Deploy as APIs for real-time inference
 - Explore transfer learning

## 🤝 Contributing
 Contributions, issues, and feature requests are welcome!
 Open an issue or submit a pull request.

## 📜 License
 This project is licensed under the MIT License.
