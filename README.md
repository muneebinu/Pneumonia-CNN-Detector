# 🩺 Pneumonia Detection System Using MobileNet and Tkinter GUI

This project is a **desktop-based pneumonia detection system** built using a **Convolutional Neural Network (CNN)** with **MobileNet** for accurate image classification. It provides a **Tkinter GUI** for user interaction and integrates **Google Text-to-Speech (gTTS)** to deliver audio feedback on predictions.

---

## 🧠 Model Overview

- **Architecture:** MobileNet (Transfer Learning)
- **Task:** Classify chest X-ray images as `PNEUMONIA` or `NORMAL`
- **Output:** Label + Confidence + Voice feedback
- **Features:**
  - Uses a lightweight MobileNet model
  - Real-time prediction and voice result
  - Color-coded results for visual clarity

---

## 🖼️ GUI Preview

![GUI Screenshot](gui.png)
> *A simple GUI built with Tkinter. Allows users to upload chest X-ray images and get instant prediction results with spoken output.*

---

## 🚀 How to Use

### 1️⃣ Install Required Libraries

```bash
pip install tensorflow keras gtts pygame pillow
Developed by Muneeb as part of a deep learning project to detect pneumonia from medical images.
📄 License
This project is intended for educational and research purposes only.
Feel free to modify and extend it with proper attribution.
