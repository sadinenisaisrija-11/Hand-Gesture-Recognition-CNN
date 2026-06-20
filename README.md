# Hand-Gesture-Recognition-CNN
# PRODIGY_ML_04 - Hand Gesture Recognition Using CNN

## 📌 Project Overview

This project was developed as part of the **Prodigy InfoTech Machine Learning Internship**.

The objective of this task is to build a **Hand Gesture Recognition System** that can accurately identify and classify different hand gestures from image data using a Convolutional Neural Network (CNN).

---

## 🎯 Task Objective

Develop a machine learning model capable of recognizing hand gestures from images and classifying them into predefined gesture categories.

---

## 📂 Dataset

**LeapGestRecog Dataset**

The dataset contains thousands of hand gesture images organized into multiple gesture classes and subjects.

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Collection

* Loaded images from the LeapGestRecog dataset.
* Selected a subset of images for training and testing.

### 2. Data Preprocessing

* Resized images to 64×64 pixels.
* Converted images into NumPy arrays.
* Normalized pixel values.

### 3. Label Encoding

* Converted gesture labels into numerical values.
* Applied one-hot encoding for classification.

### 4. Dataset Splitting

* Training Data: 80%
* Testing Data: 20%

### 5. CNN Model Architecture

* Conv2D Layer
* MaxPooling2D Layer
* Conv2D Layer
* MaxPooling2D Layer
* Flatten Layer
* Dense Layer
* Dropout Layer
* Softmax Output Layer

### 6. Model Training

* Optimizer: Adam
* Loss Function: Categorical Crossentropy
* Epochs: 10
* Batch Size: 32

### 7. Model Evaluation

* Evaluated the model using test data.
* Generated accuracy visualization graphs.

---

## 📈 Results

* Successfully trained a CNN-based hand gesture recognition model.
* Achieved **100% Test Accuracy** on the selected dataset subset.
* Saved the trained model for future predictions.

---

## 📁 Project Structure

```text
PRODIGY_ML_04/
│
├── Hand_Gesture_Recognition.ipynb
├── gesture_model.h5
├── README.md
└── screenshots/
```

---

## 🚀 Future Improvements

* Real-time hand gesture recognition using webcam input.
* Support for additional gesture categories.
* Deployment as a web application.
* Enhanced model performance using larger datasets.


