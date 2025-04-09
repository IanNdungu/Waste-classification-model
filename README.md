# 🧠 AI-Powered Plastic vs. Non-Plastic Waste Classifier

This project is a lightweight, real-time image classification model trained using **MobileNetV2** to classify waste into two categories: **Plastic** and **Non-Plastic**. The goal is to support AI-driven waste sorting systems for industrial and environmental use.

---

## 📸 Live Webcam Use Case

This model is optimized for real-time inference using a **webcam or video feed**, making it ideal for:
- Smart recycling bins
- AI waste sorting lines
- Web apps using TensorFlow.js

---

## 🛠️ Features

- ✅ **Binary image classification** (Plastic vs Non-Plastic)
- ✅ Built on **MobileNetV2** (transfer learning)
- ✅ Optimized for **real-time inference**
- ✅ Uses **image augmentation**, **early stopping**, and **fine-tuning**
- ✅ Save model in native `.keras` format (ready for TensorFlow.js conversion)

---

## 🧪 Dataset

- ~595 images labeled **plastic**
- ~685 images labeled **non_plastic**
- Organized in the following folder structure:


---

## 📦 Installation

> 🐍 Python 3.10 is recommended

# Create virtual environment (optional)
python -m venv tf_env
source tf_env/bin/activate   # or .\tf_env\Scripts\activate on Windows

# Install required packages
pip install tensorflow opencv-python matplotlib scikit-learn
