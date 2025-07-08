# Skin-Disease-Detection-System
 It is a deep learning-based web app for early skin disease detection using CNNs. Classifies conditions like eczema, melanoma, and acne from images with real-time diagnosis, treatment suggestions, and a user-friendly Flask interface. Built with Python, TensorFlow, and OpenCV.
 ---
# 🧪 Skin Disease Detection System

A deep learning-based web application for early and accurate detection of skin diseases. This system leverages Convolutional Neural Networks (CNNs) to classify common skin conditions from uploaded images and provides real-time diagnosis with treatment suggestions.

---

## 🚀 Key Features

- 🔍 **Automated Skin Disease Detection** using trained CNNs
- 📷 Upload skin images via web interface
- ⚕️ Classifies diseases like **melanoma**, **eczema**, **acne**, and more
- 📊 Returns disease name, confidence score, and suggested treatment
- 🔒 Secure login/signup system
- 🌐 Built with **Flask**, **TensorFlow**, and **OpenCV**

---

## 💡 Use Cases

- Early detection in remote/underserved regions  
- Supplement clinical diagnostics  
- Educational tool for dermatology learning  

---

## 🧰 Tech Stack

**Frontend**:
- HTML/CSS (Bootstrap)
- JavaScript

**Backend**:
- Python 3.10
- Flask
- Keras with TensorFlow backend

**Libraries**:
- OpenCV
- NumPy, Pillow
- Matplotlib / Seaborn

**Model**:
- CNN trained on the ISIC skin disease dataset  
- Model files: `model.h5`, `model.json`

---

## 🛠️ System Requirements

**Software**:
- Python 3.10
- Docker (for deployment, optional)

**Hardware**:
- OS: Windows/Linux
- Processor: Intel i5 or above
- RAM: 8–16 GB recommended
- Disk: 256 GB SSD or 500 GB HDD
  
  ---

## 🧪 How It Works

1. **User uploads an image** (e.g., rash or skin lesion).
2. The image is **resized to 224x224**, normalized, and passed to the CNN model.
3. Model outputs:
   - Predicted skin disease
   - Confidence score
   - Suggested treatment
4. Response is returned in JSON and displayed on the dashboard.

---
## 📦 Project Structure

├── static/
├── templates/
├── model.h5
├── model.json
├── app.py
├── requirements.txt
└── README.md
