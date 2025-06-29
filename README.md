# 📦 CIFAR-10 Transfer Learning with ResNet50

A deep learning project leveraging **Transfer Learning with ResNet50** to perform high-accuracy image classification on the CIFAR-10 dataset. The model achieves **93.86% test accuracy**, demonstrating strong generalization across 10 object categories.

---

## 🔍 Project Overview

This project applies a **pretrained ResNet50 model** (from ImageNet) to classify 60x60 RGB images into 10 categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

---

## 🚀 Key Features

- ✅ **93.86% Test Accuracy** using fine-tuned ResNet50  
- 🧠 **Transfer Learning** to reduce training time and improve performance  
- 📊 Evaluation via **accuracy, loss plots**, and **confusion matrix**  
- 🧹 Clean data pipeline: extraction, resizing, normalization, label encoding  
- 🛠️ Built with **TensorFlow/Keras**, trained on Google Colab (GPU-enabled)

---

## 📁 Dataset

- **Source**: [CIFAR-10 - Kaggle](https://www.kaggle.com/c/cifar-10)
- Contains 50,000 training and 10,000 test images (32x32 pixels, 10 classes)

---

## 🏗️ Model Architecture

- Base: `ResNet50` pretrained on ImageNet  
- Top layers: Flatten → Dense(512) → Dropout(0.5) → Dense(10, softmax)  
- Loss: `categorical_crossentropy`  
- Optimizer: `Adam`  
- Metrics: `accuracy`

---

## 📈 Results

- **Final Test Accuracy**: `93.86%`  
- Training Time: ~40s per epoch  
- Visualization: Accuracy/Loss curves and Confusion Matrix

---

## 🧰 Technologies Used

- Python, TensorFlow, Keras  
- OpenCV, Pandas, Matplotlib  
- Google Colab, Kaggle CLI
