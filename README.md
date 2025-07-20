#  Deep-Learning-Based-Disease-Detection
# 🧠 Skin Disease Classification using CNN (Psoriasis, Acne, Eczema)

This repository contains a deep learning project focused on classifying dermatological conditions — **psoriasis**, **acne**, and **eczema** — using **Convolutional Neural Networks (CNNs)**. The model is built on the **VGG16** architecture and aims to assist medical professionals in early and accurate diagnosis through automated image recognition.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## 📝 Overview

Skin diseases like acne, eczema, and psoriasis are widespread and often require timely diagnosis. This project uses a CNN-based classification model that:
- Preprocesses skin images
- Extracts deep visual features
- Classifies the condition with high accuracy

It is designed to aid dermatologists and can be especially helpful in **remote areas** or regions with **limited medical resources**.

---

## 🚀 Features
✅ Image preprocessing and augmentation  
✅ Transfer learning with VGG16  
✅ Batch normalization and dropout to avoid overfitting  
✅ Evaluation using Accuracy, Precision, Recall, and F1-score  
✅ Real-world prediction on custom images  

---

## 📂 Dataset

The dataset contains labeled skin condition images classified as:
- Psoriasis
- Acne
- Eczema

> *Please ensure to download or link a dataset, or provide instructions if using a public one like DermNet or HAM10000.*

---

## 🧠 Model Architecture

- Input Layer (224x224x3)
- VGG16 Convolutional Layers (pre-trained weights)
- Flatten + Fully Connected Layers
- Dropout
- Softmax Output (3 classes)

![VGG16 Architecture](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*XH1-7eM2z7_yXrRJP9uCvA.png)

---

## 🛠 Installation

### Clone the Repository
```bash
git clone https://github.com/your-username/skin-disease-cnn.git
cd skin-disease-cnn
