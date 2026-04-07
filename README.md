<img width="2960" height="158" alt="image" src="https://github.com/user-attachments/assets/90b76030-e4aa-47b2-a7b2-14454e6f303e" />

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
2. OpenCV Preprocessing (resize, normalization)  
3. U-Net Model Inference  
4. Sigmoid + Thresholding  
5. Pixel-wise Mask Generation  
6. Visualization on Web UI  

---

## 🧠 Model Details
- Architecture: U-Net  
- Input Size: 224 × 224  
- Output: Binary segmentation mask  
- Threshold: 0.5  
- Framework: PyTorch  

---

## 🌐 Web Application (Frontend + Backend)

### 🔧 Backend (Flask)
- Handles image upload and processing  
- Loads trained model (`.pth`)  
- Performs inference using PyTorch  
- Returns mask as Base64  

### 🎨 Frontend (HTML + Tailwind CSS)
- Interactive UI  
- Upload image functionality  
- Displays:
  - Original image  
  - Detection mask  
  - Result (Real / Manipulated)  

---

## 📂 Project Structure
