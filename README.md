# 🔬 LIBS Spectral Classification using Deep Learning

This project focuses on classifying LIBS (Laser-Induced Breakdown Spectroscopy) spectral data into 12 classes using multiple deep learning architectures.

---

## 🔍 Overview

LIBS data consists of high-dimensional spectral signals (~40,000 features).  
This project explores different deep learning techniques to effectively classify such data.

---

## 🧠 Models Implemented

1. **1D CNN**
   - Extracts local spectral features
   - Baseline deep learning model

2. **CNN + LSTM**
   - CNN for feature extraction
   - LSTM for sequential learning
   - Captures temporal dependencies

3. **ResNet1D**
   - Deep residual architecture
   - Uses skip connections to improve training
   - Best for deep feature learning

4. **Autoencoder + MLP**
   - Compresses features (40002 → 128)
   - Uses latent representation for classification
   - Reduces dimensionality and noise

---

## 🔄 Pipeline
## 🔄 Pipeline

Raw Spectral Data  
→ Data Preprocessing (Scaling)  
→ Model Training (CNN / LSTM / ResNet / Autoencoder)  
→ Feature Extraction / Sequence Learning  
→ Classification (12 Classes)

---

## 📊 Model Comparison

| Model | Key Strength |
|------|-------------|
| CNN | Basic feature extraction |
| CNN + LSTM | Sequence modeling |
| ResNet1D | Deep learning with residual connections |
| Autoencoder + MLP | Dimensionality reduction |

---

## ⚙️ Technologies Used

- Python 🐍  
- PyTorch 🔥  
- NumPy & Pandas  
- Scikit-learn  
- Matplotlib  

---
## 📊 Results

| Model               | Test Accuracy | Test Loss |
|--------------------|--------------|----------|
| CNN                | **69.47%**   | 2.5597   |
| CNN + LSTM         | 55.52%       | 2.8180   |
| ResNet1D           | **67.40%**   | 3.2745   |
| Autoencoder + MLP  | 27.67%       | 3.6961   |




## 📈 Analysis

- CNN achieved the best performance with 69.47% accuracy
- ResNet1D showed strong performance due to residual connections
- CNN + LSTM struggled with sequence modeling on this dataset
- Autoencoder + MLP underperformed due to information loss in compression
