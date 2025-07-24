# Emotion-detection-Computer-Vision
Using OpenCV ( TensorFlow) 
# Real-Time Emotion Detection using CNN and OpenCV

This project is a real-time facial emotion recognition system built using **Python**, **Keras**, **OpenCV**, and a custom-trained Convolutional Neural Network (CNN). The system detects faces from a webcam or image and classifies them into one of the following emotions:

📊 **Emotion Labels**:
- Angry 😠  
- Disgust 🤢  
- Fear 😨  
- Happy 😀  
- Neutral 😐  
- Sad 😢  
- Surprise 😲

---

## 🔧 Project Components

### 1. Emotion Detection Model
- Trained on a grayscale image dataset (48x48 px).
- CNN with Conv2D, MaxPooling, Dropout, Dense layers.
- Saved as `model_file.h5`.

### 2. Real-Time Webcam Detection
- Uses OpenCV to capture video frames.
- Detects faces using Haar Cascade.
- Classifies emotions using the trained CNN model.

### 3. Static Image Emotion Detection
- Can classify emotions in pre-saved images using the same model.

---

## 📁 Directory Structure
emotion-detection/
├── model_file.h5 # Trained CNN model
├── haarcascade_frontalface_default.xml # Haar cascade for face detection
├── real_time_emotion.py # Real-time webcam-based emotion detection
├── image_emotion_detection.py # Detect emotion from a saved image
├── train_model.py # Script to train the CNN model
├── Dataset/ # Training and testing image dataset
│ ├── train/
│ └── test/
└── README.md # You're reading it :)

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

git clone https://github.com/your-username/emotion-detection.git(bash)
cd emotion-detection
2. Install Required Libraries
pip install -r requirements.txt(bash)
Required Packages:

numpy

opencv-python

tensorflow / keras

matplotlib
3. To Train Your Model (Optional)
bash
python train_model.py
To Run Real-Time Webcam Emotion Detection
bash
python real_time_emotion.py
 To Run Emotion Detection on an Image
bash
python image_emotion_detection.py
🎯 Features
Real-time face detection from webcam

Emotion classification with custom-trained CNN

Lightweight and fast

Easily extendable to use TensorFlow.js for browser deployment

🚀 Future Scope
Deploy the model on a browser using TensorFlow.js

Host on GitHub Pages or Netlify

Add voice feedback for detected emotions

Create a luxury-themed UI for AI-based emotion therapy



