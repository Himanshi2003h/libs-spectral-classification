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
