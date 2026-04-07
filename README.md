<img width="2960" height="158" alt="image" src="https://github.com/user-attachments/assets/90b76030-e4aa-47b2-a7b2-14454e6f303e" />
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/PyTorch-DeepLearning-red?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Flask-WebApp-black?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/OpenCV-ComputerVision-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/IoU-0.3214-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Dice-0.4256-purple?style=for-the-badge"/>
</p>

## 📌 Overview
DeepReveal is a deep learning-based image forensics system that detects AI-generated or manipulated regions at the pixel level.

It performs segmentation to highlight exact manipulated areas instead of simple classification.
---

## 🎥 Demo
(Add screenshot or GIF here)
---

## 🚀 Features
- Pixel-level detection  
- U-Net segmentation  
- Web-based interface  
- Upload custom images  
- Mask visualization

  ---

## 🧭 Pipeline

<details>
<summary>🔍 Click to view pipeline</summary>

Input Image  
→ Preprocessing  
→ Model  
→ Sigmoid  
→ Threshold  
→ Mask  
→ Display  

</details>


## 🧠 Model Details

<details>
<summary>📊 Click to view details</summary>

- U-Net  
- Input: 224×224  
- Output: Binary mask  
- Threshold: 0.5  
- PyTorch  

</details>


## 🔬 Preprocessing

<details>
<summary>⚙️ Click to expand</summary>

- BGR → RGB  
- Resize  
- Normalize  
- Convert to tensor  

</details>


## 🔄 Model Comparison

<details>
<summary>📈 View comparison</summary>

| Feature | Initial Model | U-Net |
|--------|-------------|------|
| Output | Coarse | Pixel-wise |
| Accuracy | Moderate | High |
| Localization | Weak | Strong |

</details>


## 🌐 Web Application

<details>
<summary>💻 View details</summary>

Backend:
- Flask  
- Model inference  

Frontend:
- HTML + Tailwind  
- Upload + result  

</details>


## 📂 Project Structure

DeepReveal/
│── app.py  
│── model_utils.py  
│── templates/  
│── models/  
│── notebooks/  
│── images/  
│── README.md  
---

## ⚙️ Installation

git clone https://github.com/your-username/DeepReveal.git  
cd DeepReveal  
pip install flask torch torchvision opencv-python numpy  
---

## 📸 Results

| Input | Output |
|------|--------|
| ![](images/demo1.png) | ![](images/demo2.png) |
---

## 📊 Output
- White → Manipulated  
- Black → Real
  ---

## 🤝 Questions & Contributions

**Let's connect or collaborate!**

- Ammu Elizabeth Alexander — [ammuelizabethalexander@gmail.com](mailto:ammuelizabethalexander@gmail.com)
- Anakha Prakash — [anakhaprakash229@gmail.com](mailto:anakhaprakash229@gmail.com)
- Aiswrya Josy — [aiswaryajosy@gmail.com](mailto:aiswaryajosy@gmail.com)
- Abin Joseph — [abinkjoseph2004@gmail.com](mailto:abinkjoseph2004@gmail.com)

---

<p align="center">
  <b>🌟 Thank you for exploring our project!<br>
</p>

