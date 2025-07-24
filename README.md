# 🧠 Pneumonia Detection using ResNet (PyTorch)

A deep learning-based medical image classification project using **PyTorch** and **ResNet-18** to detect pneumonia from chest X-ray images.

---

## 📌 Project Overview

Pneumonia is a severe lung infection that can be fatal if not detected early. This project uses **transfer learning** with **ResNet-18**, a powerful convolutional neural network, to classify chest X-ray images as **Pneumonia** or **Normal**.

---

## 📁 Project Structure

(your folder tree here)

---

## 📊 Dataset

- **Dataset**: Chest X-ray Images (Pneumonia)
- **Classes**: Pneumonia, Normal
- **Size**: ~5,000 images

---

## 🧠 Model Used

- **Architecture**: ResNet-18 (Pretrained on ImageNet)
- **Modifications**: Last fully connected layer adapted to binary classification

---

## ⚙️ How to Run

```bash
git clone https://github.com/amantikale/pneumonia-detection.git
cd pneumonia-detection
pip install -r requirements.txt
python train.py
python evaluate.py
python gradcam.py
# PyNum-AI-Developer-Projects
