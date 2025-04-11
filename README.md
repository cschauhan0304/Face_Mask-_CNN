# 😷 Face Mask Detection using CNN

A deep learning project that uses Convolutional Neural Networks (CNN) to detect whether a person is wearing a face mask or not in real-time using images or video streams.

---

## 📌 Project Overview

The goal of this project is to build a deep learning model capable of distinguishing between people **with masks** and **without masks** using a CNN. This is crucial in the current context of public health surveillance and safety enforcement.

---

## 📂 Dataset

The dataset used is a labeled collection of face images from:

📥 [Face Mask Dataset on Kaggle](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)


- Total images: ~1,375
- Preprocessing:
  - Resized to 128x128
  - Normalized pixel values
  - Converted to grayscale (optional)

---

## 🧠 Model Architecture

The model is a simple but effective **CNN** built using Keras with the following layers:


✅ Binary Classification: 0 - Without Mask | 1 - With Mask

---

## 📊 Model Performance

- **Training Accuracy**: ~98%
- **Validation Accuracy**: ~97%
- **Loss**: Converges within 10–15 epochs

### 📈 Accuracy & Loss Curves

![Accuracy Plot](assets/accuracy.png)
![Loss Plot](assets/loss.png)

---

## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/cschauhan0304/Face_Mask-_CNN/
cd Face_Mask-_CNN
