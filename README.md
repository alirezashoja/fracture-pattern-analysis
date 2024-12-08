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

## **Directory Structure**
fracture-pattern-analysis/
├── data/
│   ├── NEU_Metal_Surface_Defects/  # Original dataset folder
│   ├── X_train.npy          # Training data (excluded from repo, see below)
│   ├── X_test.npy           # Testing data (excluded from repo, see below)
│   ├── y_train.npy          # Training labels
│   ├── y_test.npy           # Testing labels
├── notebooks/
│   ├── preprocessing.ipynb  # Data preprocessing steps
│   ├── model_training.ipynb # CNN training and evaluation
├── README.md                # Project documentation
├── requirements.txt         # Python dependencies
├── .gitignore               # Excluded files and directories
└── .gitattributes           # Git LFS tracking (if applicable)