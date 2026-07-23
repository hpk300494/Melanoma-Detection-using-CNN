# 🩺 Melanoma Detection using Custom CNN

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red.svg)
![CNN](https://img.shields.io/badge/Model-CNN-success.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📌 Project Overview

This project implements a **custom Convolutional Neural Network (CNN)** to classify skin lesion images into **nine different disease categories**. The objective is to assist in the early detection of **melanoma**, one of the deadliest forms of skin cancer.

The model is built entirely using **TensorFlow and Keras** without using transfer learning, following the assignment requirements.

---

## 🎯 Objectives

- Build a custom CNN for multiclass skin lesion classification.
- Detect nine different skin disease categories.
- Reduce overfitting using data augmentation.
- Handle class imbalance using the Augmentor library.
- Improve model performance through iterative model refinement.

---

## 📂 Dataset

**Source:** International Skin Imaging Collaboration (ISIC)

- 2,357 dermoscopic images
- 9 disease classes
- Separate Train and Test directories
- ## 🔗 Dataset

The dataset used in this project is publicly available on Kaggle:

https://www.kaggle.com/datasets/nodoubttome/skin-cancer9-classesisic

Due to GitHub file size limitations, the dataset is not included in this repository.

### Classes

- Actinic Keratosis
- Basal Cell Carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented Benign Keratosis
- Seborrheic Keratosis
- Squamous Cell Carcinoma
- Vascular Lesion

> The dataset is not included in this repository due to its size.

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Augmentor
- Jupyter Notebook

---

## 📁 Repository Structure

```text
Melanoma-Detection-using-CNN
│
├── notebooks/
│   └── melanoma_detection_cnn.ipynb
│
├── images/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Workflow

1. Data Loading
2. Dataset Visualization
3. Image Preprocessing
4. CNN Model Development
5. Model Training
6. Data Augmentation
7. Class Imbalance Handling
8. Model Evaluation
9. Performance Comparison

---

## 📊 Results

The project demonstrates the complete deep learning workflow for multiclass medical image classification, including:

- Custom CNN implementation
- Image normalization
- Data augmentation
- Class balancing
- Model evaluation
- Performance improvement through iterative experimentation

The baseline CNN achieved **90.26% training accuracy** and **53.17% validation accuracy**, showing clear overfitting.

Applying data augmentation reduced the train–validation gap and produced a best validation accuracy of **58.64%**. Class balancing with Augmentor increased training accuracy substantially, but validation performance remained unstable and peaked at **62.95%**, indicating continued overfitting.

Overall, data augmentation provided the most balanced performance, while transfer learning was identified as a suitable next step for improving generalization.
---

## 📈 Future Improvements

- Transfer Learning (ResNet50, EfficientNet)
- Hyperparameter Optimization
- Early Stopping
- Learning Rate Scheduling
- Model Explainability using Grad-CAM

---

## 👩‍💻 Author

**Hanaa Parvez Khan**

PG Diploma in Machine Learning & AI
