# Hand-Gesture-Classification
A real-time hand gesture classification project using a deep learning model and live camera feed to recognize and classify static hand gestures instantly.
# 🖐️ Real-Time Hand Gesture Classification

This project implements a real-time hand gesture classification system using a deep learning model and your device's camera. It detects and classifies hand gestures from the live video feed using a Convolutional Neural Network (CNN). This system can be used for gesture-based interaction, sign language recognition, or contactless control systems.

---

## 📌 Features

- Real-time gesture detection using webcam
- Convolutional Neural Network (CNN) for gesture classification
- Custom or public dataset training
- Live camera feed integration using OpenCV
- Model saving/loading for future use
- Accuracy and loss visualization

---

## 🧠 Model Architecture

- Input: Live camera frame (resized image)
- Conv2D Layers with ReLU Activation
- MaxPooling and Dropout layers
- Dense layers for classification
- Softmax output for multi-class prediction

---

## 🗃️ Dataset

You can use:

- Public hand gesture datasets (e.g., Kaggle, Jester, etc.)
- Your own dataset with images organized in class-wise folders

Example folder structure:
dataset/
├── Thumbs_Up/
│ ├── img1.jpg
│ ├── img2.jpg
├── Peace/
│ ├── img1.jpg
│ ├── img2.jpg



---

## 🚀 How to Run

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/real-time-hand-gesture-classification.git
cd real-time-hand-gesture-classification

2. Install Dependencies
pip install -r requirements.txt
3. Train the Model (if needed)
python train.py
4. Run Real-Time Gesture Classification
python realtime_prediction.py
