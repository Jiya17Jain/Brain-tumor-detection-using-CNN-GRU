# Brain-tumor-detection-using-CNN-GRU
This repository showcases an advanced Deep Learning framework for Brain Tumor Detection and Classification using MRI imaging data. The proposed hybrid architecture combines CNN layers for high-level spatial feature extraction with GRU networks to capture complex feature dependencies, improving diagnostic performance. 
This model performs multi-class tumor classification (Glioma, Meningioma, Pituitary, No Tumor) with optimized preprocessing and augmentation, demonstrating the potential of intelligent medical imaging for early diagnosis and clinical decision support.

## 🎯Objectives

 - Detect presence of brain tumors from MRI scans

 - Classify tumors into multiple categories

 - Improve diagnostic accuracy using hybrid deep learning

 - Automate medical image analysis

## 🧬 Tumor Classes
The model classifies MRI images into:

- Glioma Tumor

- Meningioma Tumor

- Pituitary Tumor

- No Tumor

## 🏗️ Model Architecture

- CNN Layers → Spatial feature extraction

- Pooling Layers → Dimensionality reduction

- GRU Layers → Sequential feature learning

- Dense Layers → Classification

- Softmax Output → Multi-class prediction

- Hybrid CNN-GRU improves performance by combining visual + sequential learning.

## ⚙️Tech Stack
- Programming: Python
  
 - Deep Learning: TensorFlow / Keras
   
- Libraries:
  
   - NumPy

   - OpenCV

   - Matplotlib

   - Scikit-learn

- Platform: Google Colab
  
- Dataset API: Kaggle API

## 📊 Training Pipeline

1. Data loading from MRI dataset

2. Image resizing & normalization
   
3. Data augmentation

4. Train-validation split

5. CNN feature extraction

6. GRU sequence learning

7. Model training & evaluation
