# **Fracture Pattern Analysis Using AI**

## **Overview**
This project implements a Convolutional Neural Network (CNN) to analyze fracture patterns in materials. The model is trained on the **NEU Metal Surface Defects Dataset** to classify surface defects into six categories:
1. Crazing
2. Inclusion
3. Patches
4. Pitted Surface
5. Rolled-in Scale
6. Scratches

The project demonstrates how deep learning techniques can assist in identifying and classifying material defects, contributing to automated quality assurance in industrial settings.

---

## **Features**
- **Data Preprocessing**: Resize, normalize, and prepare the dataset.
- **CNN Architecture**: A convolutional neural network for defect classification.
- **Model Evaluation**: Metrics such as accuracy and loss visualized during training and testing.
- **Reproducibility**: Preprocessing and training code available in Jupyter notebooks.

---

---

## **Dataset**
The dataset used in this project is the **NEU Metal Surface Defects Dataset**, which contains grayscale images of six types of metal surface defects.

### **Download the Dataset**
The dataset files (`X_train.npy`, `X_test.npy`, etc.) are excluded from the repository due to file size limitations. You can obtain them as follows:
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/fantacher/neu-metal-surface-defects-data).
2. Extract the dataset to the `data/NEU_Metal_Surface_Defects` directory.
3. Run the `preprocessing.ipynb` notebook to preprocess the dataset.

---

## **How to Use**

### **1. Install Dependencies**
Make sure you have Python installed. Install the required libraries using:
```bash
pip install -r requirements.txt