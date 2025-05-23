# Dogs vs. Cats Redux 🐶🐱 - Image Classification

This repository contains my solution to the Kaggle competition: **Dogs vs. Cats Redux: Kernels Edition**. The goal is to classify pet images as either a dog (label `1`) or a cat (label `0`) using deep learning.

---

## 🧠 Problem Statement

Classify 12,500 test images from a dataset of pet photographs into two categories: dogs or cats. The challenge lies in capturing subtle differences under varied lighting, angles, and postures.

---

## 🔍 Methodology

- **Data Preprocessing**:
  - Resized images to `224x224`
  - Used `ImageDataGenerator` for data augmentation
- **Baseline Model**:
  - A custom CNN trained from scratch
- **Transfer Learning Models**:
  - `VGG16`, `EfficientNetB0`, and `MobileNetV2` with frozen base and custom dense head
- **Evaluation**:
  - Compared accuracy, loss, and convergence speed
  - Used `early stopping` and `model checkpointing` for optimal training

---

## 🛠️ Tech Stack

- Python, Keras, TensorFlow
- Jupyter Notebook
- Matplotlib / Seaborn for visualization

---

## 📁 Folder Overview

- `notebooks/`: Jupyter notebook with model exploration
- `src/`: (Optional) Python scripts for modular training/inference
- `data/`: Dataset info (actual images not uploaded due to size)
- `images/`: Visuals or prediction examples
- `requirements.txt`: Python dependencies

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebooks/HW4_Q2_ApurvaBaru.ipynb

