## 🎯 Image Classification using CNN

This project builds and trains a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset. It applies data preprocessing, normalization, image visualization, CNN architecture design, training, and evaluation to achieve strong performance on image recognition tasks.

---

## 📌 Project Overview

The goal of this project is to classify small RGB images into 10 categories using deep learning.
The model is built using the Keras Sequential API and includes multiple convolution and pooling layers followed by dense layers for classification.
The network is trained for 10 epochs and reaches approximately **70% test accuracy**.

---

## 📂 Dataset

Dataset used: **CIFAR-10** (via TensorFlow)

Contains:

* 60,000 images (32×32 pixels)
* 10 classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)
* 50,000 training images
* 10,000 testing images

The dataset downloads automatically—no setup required.

---

## 🛠️ Tools & Technologies

* TensorFlow
* Keras
* Python
* NumPy
* Matplotlib
* Jupyter Notebook / Google Colab

---

## 🧹 Data Preprocessing

* Normalized pixel values from 0–255 to 0–1
* Visualized sample training images
* Checked labels and image shapes
* Prepared dataset for CNN input format (32×32×3 RGB)

---

## 🔍 CNN Architecture (Model Design)

The CNN includes:

* **Conv2D (32 filters)**
* **MaxPooling2D**
* **Conv2D (64 filters)**
* **MaxPooling2D**
* **Conv2D (64 filters)**
* **Flatten layer**
* **Dense(64)**
* **Dense(10)** final classification layer

Optimizer: **Adam**
Loss: **SparseCategoricalCrossentropy**
Metric: **Accuracy**

---

## 🤖 Training & Evaluation

* Trained for **10 epochs**
* Plotted training and validation accuracy curves
* Evaluated on the test dataset

**Test Accuracy:** ~70%
A solid performance for a simple CNN without data augmentation.

---

## 📊 Results Summary

* Effective CNN for CIFAR-10 image classification
* Good baseline accuracy
* Clear training vs validation accuracy plots
* Architecture suitable for further improvements (augmentation, batch norm, deeper layers)

---

## 🚀 How to Run

Install the required packages:

```bash
pip install tensorflow numpy matplotlib
```

Run the Python script:

```bash
python image_classification_using_cnn.py
```

Or open the notebook:

```
image_classification_using_cnn.ipynb
```

---

## 📁 Project Structure

```
image_classification_cnn/
│── image_classification_using_cnn.ipynb
│── image_classification_using_cnn.py
│── README.md
```

---

## 📬 Contact

Created by **Asem Ahmed**
