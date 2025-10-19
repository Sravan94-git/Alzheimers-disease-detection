# 🧠 Alzheimer's Diagnosis with Deep Learning & XAI

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Framework](https://img.shields.io/badge/Framework-TensorFlow/Keras-orange.svg)](https://www.tensorflow.org/)

This project addresses the challenge of ambiguous Alzheimer's disease diagnosis by employing deep learning models to analyze medical imaging. The goal is to provide a more transparent, accurate, and reliable decision-making tool for clinicians and patients. By comparing various neural network architectures on different image formats, this work identifies high-performing models and enhances diagnostic confidence through explainable AI.

***

### 📌 Project Overview

The core of this project is to enhance the precision of Alzheimer's diagnosis using four distinct deep learning models: **CNN, AlexNet, DenseNet, and ResNet**. A key aspect of the research involves a comparative analysis of model performance on the original image dataset versus the same dataset converted to the HSV (Hue, Saturation, Value) color space.

To tackle class imbalance, a common issue in medical datasets, the **Synthetic Minority Oversampling Technique (SMOTE)** is used. The project not only aims for high accuracy but also for model transparency, providing understandable explanations for the models' predictions to assist doctors in patient care.

***

### ✨ Key Features

* **Multi-Model Architecture:** Implements and evaluates four powerful deep learning models for a comprehensive comparison.
* **Color Space Analysis:** Investigates the impact of color spaces by training and testing on both original (RGB) and HSV formatted images.
* **Class Imbalance Handling:** Utilizes SMOTE to create a balanced dataset, preventing model bias towards the majority class and improving minority class detection.
* **High Diagnostic Accuracy:** Achieved excellent results, with **CNN** being the top performer on original images and **DenseNet** on HSV images.
* **Explainable AI (XAI):** Focuses on model interpretability, allowing clinicians to understand the "why" behind a diagnosis, thereby increasing trust and confidence in the system.

***



### 📊 Results & Findings

* On the **original (RGB) dataset**, the custom **Convolutional Neural Network (CNN)** achieved the highest diagnostic accuracy.
* On the **HSV-converted dataset**, the **DenseNet** architecture demonstrated superior performance.
* The use of SMOTE was crucial in improving the models' ability to correctly identify minority classes, which is often the most critical task in disease diagnosis.


***

### 🛠️ Tech Stack

* **Programming Language:** Python 3
* **Deep Learning Frameworks:** TensorFlow, Keras
* **Data Manipulation:** Pandas, NumPy, OpenCV
* **Class Balancing:** `imbalanced-learn` (for SMOTE)
* **Data Visualization:** Matplotlib, Seaborn
* **Development Environment:** Jupyter Notebook / Google Colab

***

