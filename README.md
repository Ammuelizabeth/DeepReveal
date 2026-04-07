<img width="2960" height="158" alt="image" src="https://github.com/user-attachments/assets/90b76030-e4aa-47b2-a7b2-14454e6f303e" />

# 🔍 DeepReveal: Pixel-wise AI Content Detection using Deep Learning & Image Forensics

## 📌 Overview
DeepReveal is a deep learning-based image forensics system that detects AI-generated or manipulated regions at the pixel level. Instead of simply classifying images as real or fake, it performs segmentation to highlight the exact regions of manipulation.

The project combines deep learning, computer vision, and a web-based interface to create a complete AI-powered detection system.

---

## 🚀 Features
- Pixel-level manipulation detection  
- U-Net based segmentation model  
- Real-time detection via web interface  
- Upload and analyze custom images  
- Visual output with detection masks  
- Automatic manipulation detection logic  

---

## 🏗️ System Architecture
1. Input Image  
2. OpenCV Preprocessing  
3. U-Net Model  
4. Sigmoid + Threshold  
5. Mask Generation  
6. Web Display  

---

## 🧠 Model Details
- Architecture: U-Net  
- Input Size: 224 × 224  
- Output: Binary mask  
- Framework: PyTorch  

---

## 🌐 Web Application

### Backend (Flask)
- Handles image upload  
- Runs model  
- Returns result  

### Frontend (HTML)
- Upload image  
- Shows result  
- Displays mask  

---

## 📂 Project Structure
DeepReveal/
│── app.py
│── model_utils.py
│── templates/
│   ├── index.html
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

## ▶️ Usage

Run:
python app.py  

Open:
http://127.0.0.1:5000  

---

## 📸 Demo
(Add your screenshots here)

---

## 📊 Output
White → Fake  
Black → Real  

---

## 👩‍💻 Author
Ammu Elizabeth Alexander



