# 🕵️‍♂️ DeepReveal
## AI-Generated Image Manipulation Detection using Deep Learning

<p align="center">
  <img src="images/home_page.png" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/PyTorch-DeepLearning-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Flask-WebApp-black?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/OpenCV-ComputerVision-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/U--Net-Segmentation-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/IoU-0.3214-yellow?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Dice-0.4256-purple?style=for-the-badge"/>
</p>

---

# 📌 Overview

DeepReveal is a deep learning-based image forensics system developed to detect AI-generated or manipulated regions at the pixel level.

Unlike traditional classification approaches, DeepReveal performs semantic segmentation to precisely localize manipulated regions within an image using a U-Net segmentation architecture.

The system includes:

- Deep learning segmentation model
- Computer vision preprocessing pipeline
- Flask-powered web application
- Pixel-level manipulation visualization

This project was developed using PyTorch, OpenCV, and Flask.

---

# 🎥 Project Demo

<p align="center">
  <img src="images/analyse_page.png" width="900">
</p>

---

# 🚀 Features

✅ Pixel-level manipulation detection  
✅ U-Net segmentation architecture  
✅ Real-time image analysis  
✅ Flask-based web application  
✅ Upload and analyze custom images  
✅ Binary mask visualization  
✅ Manipulated region localization  
✅ Deep learning inference pipeline  

---

# 🧠 Model Details

| Component | Details |
|-----------|---------|
| Architecture | U-Net |
| Framework | PyTorch |
| Input Size | 224 × 224 |
| Output | Binary Segmentation Mask |
| Threshold | 0.5 |
| Task | Manipulation Segmentation |

---

# 🧭 DeepReveal Pipeline

<details>
<summary>🔍 Click to View Pipeline</summary>

```text
Input Image
     ↓
Preprocessing
     ↓
U-Net Segmentation Model
     ↓
Sigmoid Activation
     ↓
Thresholding
     ↓
Binary Mask Generation
     ↓
Manipulated Region Detection
```

</details>

---

# 🔬 Preprocessing & Inference

<details>
<summary>⚙️ View Processing Steps</summary>

## Image Preprocessing
- BGR → RGB conversion
- Resize to 224 × 224
- Pixel normalization [0,1]
- Tensor conversion

## Inference Pipeline
- Forward propagation
- Sigmoid activation
- Thresholding at 0.5
- Binary mask generation

## Output Interpretation
- ⚪ White Pixels → Manipulated Region
- ⚫ Black Pixels → Authentic Region

</details>

---

# 🌐 Web Application

## 🏠 Home Page

<p align="center">
  <img src="images/home_page.png" width="900">
</p>

---

## 🔍 Analyze Page

<p align="center">
  <img src="images/analyse_page.png" width="900">
</p>

---

## 📄 About Page

<p align="center">
  <img src="images/about_page.png" width="900">
</p>

---

# 📸 Prediction Results

## 🖼️ Real vs Fake Detection

| Real Image | Fake Image |
|------------|------------|
| <img src="images/test_real.png" width="350"> | <img src="images/test_fake.png" width="350"> |

---

## 🎯 Manipulated Region Detection

<p align="center">
  <img src="images/test_fake_region.png" width="600">
</p>

---

# 📊 Model Performance Metrics

<p align="center">
  <img src="images/model_performance_matrics.png" width="700">
</p>

---

# 🔍 Initial Model Testing

<p align="center">
  <img src="images/initial_model_test.png" width="700">
</p>

---

# 🔄 Model Comparison

| Feature | Initial Model | U-Net |
|----------|---------------|-------|
| Output Type | Classification | Segmentation |
| Localization | Weak | Strong |
| Pixel-level Detection | ❌ | ✅ |
| Visualization | Limited | Detailed |
| Detection Accuracy | Moderate | High |

---

# 📂 Project Structure

```bash
DeepReveal/
│── app.py
│── model_utils.py
│── models/
│── templates/
│── static/
│── notebooks/
│── images/
│── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/Ammuelizabeth/DeepReveal.git
cd DeepReveal
```

## Install Dependencies

```bash
pip install flask torch torchvision opencv-python numpy
```

## Run Application

```bash
python app.py
```

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Core Programming |
| PyTorch | Deep Learning |
| OpenCV | Image Processing |
| Flask | Web Backend |
| HTML | Frontend |
| Tailwind CSS | UI Design |

---

# 📊 Evaluation Metrics

| Metric | Score |
|--------|------|
| IoU Score | 0.3214 |
| Dice Coefficient | 0.4256 |

---

# 🤝 Contributors

### 👩‍💻 Team Members

- Ammu Elizabeth Alexander  
- Anakha Prakash  
- Aiswrya Josy  
- Abin Joseph  

---

# 📬 Contact

📧 ammuelizabethalexander@gmail.com

---

# ⭐ Support

If you found this project useful, consider giving this repository a ⭐ on GitHub.

---

<p align="center">
  <b>Made with ❤️ using PyTorch, OpenCV, and Flask</b>
</p>
