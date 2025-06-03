# Pneumonia Detection using CNN (VGG16) and Flask Web App

This project uses deep learning (specifically the VGG16 model) to detect pneumonia from chest X-ray images. A pre-trained `.h5` model is deployed in a Flask-based web application that allows users to upload X-ray images and receive predictions.

---

## 📂 Dataset

- Total Images: **5,000**
- Source: Chest X-ray images categorized into `Pneumonia` and `Normal`.
- Format: JPEG/PNG image files
- Preprocessing: Images were resized and normalized before feeding into the model.

---

## 🧠 Model

- **Architecture:** VGG16 (pre-trained on ImageNet)
- **Training:**
  - Custom top layers added for binary classification
  - Trained on 5,000 image dataset
  - Saved model file: `vgg16_pneumonia.h5`

---

## 🖥️ Web App

- Built with **Flask**
- Features:
  - Home page with image upload interface
  - Displays prediction: **Pneumonia Positive** or **Negative**
- Run locally in a browser

---

## 📁 Project Structure

