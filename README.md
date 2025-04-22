# 👤 TinyML Person Detection

This repository contains a **TinyML** project for real-time person and face detection using Edge Impulse and a custom face detection notebook. It’s designed for deployment on edge devices such as the Arduino Nano 33 BLE Sense, offering efficient ML inference directly on the device.

🌐 **Live Project Link**: [View on Edge Impulse Studio](https://studio.edgeimpulse.com/public/613078/live)

📓 **Notebook**: [`face_detection.ipynb`](./face_detection.ipynb)

---

## 🚀 Overview

This project combines a person detection model trained via Edge Impulse with a custom face detection pipeline. It demonstrates how embedded ML can be used for both object and facial presence detection in resource-constrained environments.

### 🔍 Key Features

- Real-time detection of persons and faces
- Uses both Edge Impulse's visual model and a custom notebook
- Optimized for low-power embedded devices
- Deployable on:
  - Arduino Nano 33 BLE Sense
  - Raspberry Pi
  - STM32 boards

---

## 📊 Dataset and Model Training

- **Data Collected**: Images labeled as `person` and `no person`
- **Preprocessing**: Grayscale conversion, image normalization
- **Model**: Convolutional Neural Network (CNN)
- **Tools**: Edge Impulse Studio + Custom Jupyter Notebook

---

## 📓 About the Notebook

The `face_detection.ipynb` notebook includes:

- OpenCV-based face detection using Haar cascades
- Live camera frame reading and face bounding box visualization
- Additional logic for model integration or local testing
- Useful for training dataset collection or supplementary analysis

---

## 🛠️ Getting Started

To run this project:

1. Clone this repository
2. Open `face_detection.ipynb` in Jupyter Notebook or Google Colab
3. Run the Edge Impulse model on your device by:
   - Visiting the [Edge Impulse Project](https://studio.edgeimpulse.com/public/613078/live)
   - Connecting your device using Edge Impulse CLI
   - Deploying the model

---

## 📦 Deployment Options

- **Arduino Library**
- **WebAssembly**
- **Linux CLI**
- **Precompiled Firmware**

---

## 🤖 Tech Stack

- Edge Impulse
- TinyML
- OpenCV (Python)
- Jupyter Notebook
- Embedded C/C++

---

Built with ❤️ using Edge Impulse, OpenCV, and TinyML.
