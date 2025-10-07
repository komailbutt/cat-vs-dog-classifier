# 🐶🐱 Cat vs Dog Image Classifier

A deep learning project that classifies images of **cats** and **dogs** using a **Convolutional Neural Network (CNN)** built with TensorFlow and Keras.  
This repository demonstrates a complete machine learning workflow — from data preprocessing and training to evaluation and prediction on unseen data.

---

## 📘 Overview

This project aims to automatically identify whether an input image contains a **cat** or a **dog**.  
It uses a CNN model trained from scratch on the Kaggle *Dogs vs Cats* dataset.  
The model achieves high accuracy and can predict unseen images, demonstrating the power of convolutional neural networks in image classification.

---

## 📂 Dataset

The dataset is based on the [Kaggle Dogs vs Cats dataset](https://www.kaggle.com/datasets/salader/dogsvscats/data).

### Directory Structure
- **Train set:** Used for model training  
- **Test set:** Used for model evaluation  
- **Unseen image:** A separate image (`unseen_dog.jpg`) used to demonstrate model generalization  

---

## ⚙️ Features

- 📦 Image preprocessing and normalization using `ImageDataGenerator`  
- 🧠 CNN model built from scratch using Keras Sequential API  
- 🔄 Data augmentation to improve generalization and reduce overfitting  
- 📊 Model evaluation with training/test accuracy and loss visualization  
- 🐕 Prediction on an unseen dog image  

---

## 🧠 Model Architecture

A simple yet effective **Convolutional Neural Network (CNN)** built from scratch:
- **Activation Functions:** ReLU (hidden layers), Sigmoid (output)  
- **Loss Function:** Binary Crossentropy  
- **Optimizer:** Adam  
- **Metric:** Accuracy  

This architecture balances simplicity and performance, suitable for small to medium-sized image datasets.

