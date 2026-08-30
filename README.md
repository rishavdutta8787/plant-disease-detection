# 🌱 Plant Disease Detection

An end-to-end plant disease detection project combining classical machine learning, deep learning and Edge AI deployment.

## 📌 Project Overview

This project explores plant disease classification using:

- Classical Machine Learning
- Artificial Neural Networks
- Convolutional Neural Networks
- Edge AI

The project also includes deployment of a quantized model on an ESP32-CAM for on-device inference.

## 🧠 Machine Learning

The project explored:

- Logistic Regression
- Random Forest
- K-Nearest Neighbors (KNN)
- SMOTE for handling class imbalance
- Hyperparameter tuning

## 🤖 Deep Learning

ANN and CNN models were developed for plant disease classification.

The CNN achieved 97% test accuracy on the potato leaf classification task.

## ⚡ Edge AI

An INT8-quantized TensorFlow Lite model was deployed on an ESP32-CAM for on-device inference.

## 🛠️ Technologies

- Python
- scikit-learn
- TensorFlow / Keras
- CNN
- Edge Impulse
- TensorFlow Lite
- ESP32-CAM

## 📂 Project Structure

```text
plant-disease-detection/
│
├── README.md
├── notebooks/
├── models/
├── edge-ai/
├── results/
└── requirements.txt
