# 🩺 Skin Cancer Classification using HAM10000 (Skin Cancer MNIST)

## 📌 Project Overview

Skin cancer is one of the most common forms of cancer worldwide. Early detection can significantly improve treatment outcomes. This project uses Deep Learning and Convolutional Neural Networks (CNNs) to classify skin lesion images from the HAM10000 dataset into seven diagnostic categories.

The model is trained on dermatoscopic images and aims to assist healthcare professionals by providing automated skin lesion classification.

---

## 📊 Dataset

This project uses the **HAM10000 (Human Against Machine with 10,000 Training Images)** dataset, commonly referred to as the **Skin Cancer MNIST** dataset.

### Dataset Statistics

* Total Images: 10,015
* Number of Classes: 7
* Image Type: RGB Dermatoscopic Images

### Lesion Classes

| Class | Description                                     |
| ----- | ----------------------------------------------- |
| akiec | Actinic Keratoses and Intraepithelial Carcinoma |
| bcc   | Basal Cell Carcinoma                            |
| bkl   | Benign Keratosis-like Lesions                   |
| df    | Dermatofibroma                                  |
| nv    | Melanocytic Nevi                                |
| mel   | Melanoma                                        |
| vasc  | Vascular Lesions                                |

---

## 🎯 Objectives

* Perform image preprocessing and augmentation.
* Build and train a CNN model for skin lesion classification.
* Evaluate model performance using standard metrics.
* Visualize predictions and confusion matrix.
* Explore transfer learning techniques for improved accuracy.

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* OpenCV

---

## 📈 Evaluation Metrics

Model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report
* Confusion Matrix

---

## 🔍 Sample Prediction

```python
prediction = model.predict(image)
print("Predicted Class:", prediction)
```

Example Output:

```text
Predicted Class: Melanoma
Confidence: 96.4%
```

---

## 📷 Visualizations

* Training vs Validation Accuracy
* Training vs Validation Loss
* Confusion Matrix
* Sample Predictions

---
