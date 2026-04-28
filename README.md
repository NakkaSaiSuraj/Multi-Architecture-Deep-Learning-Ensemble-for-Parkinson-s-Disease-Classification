# 🧠 Parkinson’s Disease Detection from Brain MRI

## 📌 Overview

This project detects Parkinson’s Disease from brain MRI images using a deep learning ensemble of multiple architectures. The pipeline focuses on accuracy, proper validation, and interpretability.

---

## 🚀 Features

* 🧠 Multiple deep learning models (CNN + Transformer)
* 🔁 Patient-level cross-validation to prevent data leakage
* 🎯 Advanced augmentation (MixUp, CutMix, Random Erasing)
* 🤝 Ensemble learning (averaging, weighted, stacking)
* 📊 Statistical validation (bootstrap, McNemar test)
* 📉 Model calibration using temperature scaling
* 🔍 Grad-CAM for explainability

---

## 🤖 Models

* EfficientNetV2-S
* DenseNet-169
* ConvNeXt-Small
* ViT-B/16
* Swin Transformer-Small
* MaxViT-Tiny

---

## 🧬 Dataset

* 📦 831 MRI images
* 🏷️ Classes: Parkinson’s and Normal
* ⚠️ Patient-wise splitting used for training and validation

---

## 📈 Results

* 🏆 Best single model AUC: 0.962
* 🚀 Final ensemble AUC: 0.973
* 📊 Accuracy: 95.8%

---

## 🏗️ Project Structure

```bash id="3g9m8s"
src/
  data/
  models/
  training/
  evaluation/
  ensemble/
```

---

## ⚙️ How to Run

```bash id="m2k8ds"
pip install -r requirements.txt
python src/training/train.py
```

---

## 👨‍💻 Authors

* Prudvi Thapaswi Rahul
* Nakka Sai Suraj
* Durisety Bhargav Ram
