# 🧠 Alzheimer's Diagnosis with Deep Learning & Explainable AI (XAI)

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Framework](https://img.shields.io/badge/Framework-TensorFlow/Keras-orange.svg)](https://www.tensorflow.org/)

This project presents an AI-powered approach for the early diagnosis of **Alzheimer's disease** using deep learning and Explainable AI (XAI). The system analyzes brain MRI images to classify different stages of Alzheimer's disease, assisting clinicians in making faster and more reliable diagnostic decisions. By leveraging advanced convolutional neural networks and transfer learning architectures, the project aims to improve diagnostic accuracy while reducing dependency on manual image interpretation.

The study compares the performance of multiple deep learning models trained on both **RGB (original)** and **HSV color space** images to evaluate the influence of image representation on classification accuracy. To address class imbalance, **SMOTE (Synthetic Minority Oversampling Technique)** is applied, ensuring fair model learning across all disease categories. Furthermore, Explainable AI techniques are incorporated to provide visual insights into model predictions, making the decision-making process more transparent and trustworthy for healthcare professionals.

---

## ✨ Key Features

- **Multi-Model Deep Learning Comparison**
  - Implements and evaluates four powerful deep learning architectures, including CNN and DenseNet, to identify the best-performing model for Alzheimer's disease classification.

- **Color Space Analysis**
  - Compares model performance on both **RGB** and **HSV** formatted MRI images to study the impact of color representation on diagnostic accuracy.

- **Comprehensive Data Preprocessing**
  - Performs image resizing, normalization, augmentation, and preprocessing to improve model robustness and generalization.

- **Class Imbalance Handling**
  - Utilizes **SMOTE (Synthetic Minority Oversampling Technique)** to balance the dataset, reducing bias toward majority classes and improving minority class prediction.

- **Performance Evaluation**
  - Evaluates models using multiple metrics including:
    - Accuracy
    - Precision
    - Recall
    - F1-Score
    - Confusion Matrix
    - Training & Validation Curves

- **High Diagnostic Accuracy**
  - Achieved excellent classification performance:
    - **CNN** delivered the highest accuracy on RGB images.
    - **DenseNet** achieved the best performance on HSV images.

- **Explainable AI (XAI)**
  - Integrates Explainable AI techniques to visualize and interpret model predictions, helping clinicians understand which regions of MRI scans contribute most to the diagnosis.

- **Clinical Decision Support**
  - Designed as an AI-assisted diagnostic tool that enhances medical decision-making by providing accurate, interpretable, and reliable predictions.

---

## 🛠️ Tech Stack

- **Programming Language:** Python 3
- **Deep Learning Frameworks:** TensorFlow, Keras
- **Machine Learning:** Scikit-learn
- **Data Manipulation:** Pandas, NumPy
- **Computer Vision:** OpenCV
- **Class Balancing:** imbalanced-learn (SMOTE)
- **Data Visualization:** Matplotlib, Seaborn
- **Development Environment:** Jupyter Notebook / Google Colab

---

## 🎯 Project Objectives

- Develop an automated deep learning system for Alzheimer's disease diagnosis using MRI images.
- Compare the effectiveness of multiple neural network architectures.
- Evaluate the impact of RGB and HSV image representations on classification performance.
- Improve classification reliability by addressing class imbalance using SMOTE.
- Increase transparency through Explainable AI techniques.
- Provide a trustworthy AI-based clinical decision support system for early Alzheimer's diagnosis.
