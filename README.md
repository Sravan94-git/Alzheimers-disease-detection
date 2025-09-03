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

### ⚙️ Methodology

The project workflow is structured as follows:

1.  **Data Collection:** Utilization of a standard medical imaging dataset for Alzheimer's disease.
2.  **Data Preprocessing:**
    * Cleaning and resizing of images to a uniform dimension.
    * Creation of two distinct datasets: the original (RGB) and a version converted to HSV color space.
    * Application of **SMOTE** to the training set to balance the distribution of diagnostic classes (e.g., Non-Demented, Mild Demented, etc.).
3.  **Model Training:**
    * Training four separate models (Custom CNN, AlexNet, DenseNet, ResNet) on the original preprocessed dataset.
    * Training the same four models on the HSV preprocessed dataset.
4.  **Model Evaluation:**
    * Assessing the performance of each model using key metrics such as accuracy, precision, recall, and F1-score.
    * Generating confusion matrices to visualize classification performance.
5.  **Comparative Analysis:** Comparing the results to determine the best-performing model-and-dataset combination.

***

### 📊 Results & Findings

* On the **original (RGB) dataset**, the custom **Convolutional Neural Network (CNN)** achieved the highest diagnostic accuracy.
* On the **HSV-converted dataset**, the **DenseNet** architecture demonstrated superior performance.
* The use of SMOTE was crucial in improving the models' ability to correctly identify minority classes, which is often the most critical task in disease diagnosis.

*(You could add a results table or confusion matrix image here for better visualization)*

***

### 🛠️ Tech Stack

* **Programming Language:** Python 3
* **Deep Learning Frameworks:** TensorFlow, Keras
* **Data Manipulation:** Pandas, NumPy, OpenCV
* **Class Balancing:** `imbalanced-learn` (for SMOTE)
* **Data Visualization:** Matplotlib, Seaborn
* **Development Environment:** Jupyter Notebook / Google Colab

***

### 🚀 Getting Started

Follow these instructions to set up and run the project locally.

#### 1. Prerequisites

* Python 3.8 or newer
* `pip` or `conda` package manager

#### 2. Clone the Repository

```
git clone https://github.com/Sravan94-git/Alzheimers-disease-detection.git
cd Alzheimers-disease-detection
```

#### 3. Set Up the Dataset
```
This project requires a medical imaging dataset. A common choice is the Alzheimer's Dataset (4 class of images) available on Kaggle.
1. Download the dataset from Kaggle.
2. Unzip the folder and place it in the project's root directory.
```
#### 4. Install Dependencies
```
It is recommended to use a virtual environment.
# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On macOS/Linux
# venv\Scripts\activate    # On Windows

# Install required packages
pip install -r requirements.txt
```
