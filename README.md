# 🚦 Road Sign Detection System using YOLOv8

A deep learning–based Road Sign Detection System built using **YOLOv8** to automatically detect and localize traffic signs from images.  
The model is trained on a **Roboflow self-driving car dataset** and tested on real-world road images using **Google Colab**.

This project demonstrates the application of object detection in intelligent transportation systems and autonomous driving.

---

## ✨ Key Features
- 🚘 Real-time road sign detection using YOLOv8
- 🧠 Custom-trained model on a self-driving car dataset
- 🖼️ Image-based inference and visualization
- ☁️ Fully compatible with Google Colab (GPU support)
- 📦 Dataset integration via Roboflow API

---

## 🧠 Model Architecture
- **YOLOv8 (Ultralytics)**  
  A state-of-the-art, single-stage object detection model known for high speed and accuracy.

---

## 📂 Dataset Details
- **Platform:** Roboflow  
- **Workspace:** `selfdriving-car-qtywx`  
- **Project:** `self-driving-cars-lfjou`  
- **Version:** 6  
- **Annotation Format:** YOLOv8  

The dataset is automatically downloaded using the Roboflow API to ensure reproducibility.

---

## ⚙️ Installation & Setup (Google Colab)

```bash
pip install ultralytics roboflow
