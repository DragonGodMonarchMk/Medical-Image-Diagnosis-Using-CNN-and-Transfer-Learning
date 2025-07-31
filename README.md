# Medical-Image-Diagnosis-Using-CNN-and-Transfer-Learning
A deep learning pipeline for classifying medical images with CNNs and transfer learning to aid in automatic diagnosis. The project explores advanced architectures and model evaluation metrics to improve healthcare analytics.
# 🩺 Medical Diagnosis from Medical Images using CNN & Transfer Learning

This project leverages Convolutional Neural Networks (CNNs) and pre-trained models (transfer learning) to automate medical image classification tasks. It targets early and accurate diagnosis of diseases using advanced deep learning architectures, supporting potential healthcare applications.

---

## 📌 Project Objectives

- Develop a medical image classifier using deep learning
- Improve accuracy through transfer learning (pre-trained models)
- Evaluate model performance with metrics like accuracy, loss, and confusion matrix
- Build a reproducible pipeline for further research or deployment

---

## 🧪 Techniques Used

- **Image Preprocessing:** resizing, normalization, data augmentation
- **CNN Architecture:** custom layers + global pooling and dense output layers
- **Transfer Learning:** integration of pre-trained models such as VGG16, ResNet50, or EfficientNet
- **Model Evaluation:** training/validation accuracy & loss, confusion matrix, precision-recall

---

## 🧾 Files Included

| File Name                                       | Description                                       |
|------------------------------------------------|---------------------------------------------------|
| `medical-diagnosis-with-cnn-transfer-learning.ipynb` | Jupyter notebook containing data prep, model training, evaluation, and visualizations |
| `best_model.keras`                             | Saved model (if applicable) for future inference |

---

## ⚙️ Installation

Install the required Python libraries:

```bash
pip install tensorflow matplotlib numpy scikit-learn opencv-python
