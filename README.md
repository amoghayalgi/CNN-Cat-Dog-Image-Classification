# 🐶🐱 Dogs vs. Cats Image Classification (CNN + Transfer Learning)

## 📘 Overview
This project builds a high performance image classifier for the Kaggle Dogs vs. Cats Redux competition using Convolutional Neural Networks (CNNs) and transfer learning.  

The goal was to design an efficient training pipeline, experiment with modern architectures, and optimize for low log loss and high validation accuracy.  

The final model achieves 95%+ validation accuracy and a log loss of 0.05, placing it on par with the top ~20% of Kaggle submissions.

---

## ✨ Key Features
- Transfer Learning with EfficientNetB0/B3 and ResNet50V2  
- Data Augmentation including flips, color jitter, rotation, and zoom  
- Label smoothing and log-loss optimization  
- Batch size experimentation (32, 64) for stability and speed  
- Prediction clipping to reduce overconfident outputs  
- Clean, modular training pipeline for reproducibility  

---

## 🧠 Technical Stack & Concepts

### ⚙️ Deep Learning Framework
- TensorFlow / Keras  
- Pretrained ImageNet weights for transfer learning  

### 🔍 Core Concepts Used
- CNN Feature Extraction  
- Transfer Learning & Fine Tuning  
- Data Augmentation to reduce overfitting  
- Batch Normalization & Regularization  

---

## 🧪 Model Variants Explored

The following configurations were tested:  

### 🔎 Exploration Phase
- EfficientNetB0  
- EfficientNetB3  
- ResNet50V2  
- Full augmentation (flip, color jitter)  

### 🚀 Optimized Phase
- ResNet50V2 + rotation + zoom  
- Batch size = 32 or 64  

---

## 📊 Results

### 🏁 Final Model Performance
- Validation Accuracy: 95%+  
- Log Loss: 0.05  
- Kaggle Standing: Comparable to top 20% of leaderboard submissions  

### 💡 Why It Performs Well
- ResNet architectures provide strong feature extraction  
- Augmentation reduces overfitting  
- Label smoothing improves generalization  
- Prediction clipping stabilizes log-loss  

---

## 🗂 Repository Structure
├── CATvsDOG_CNN.ipynb # Full Jupyter notebook with code and results
