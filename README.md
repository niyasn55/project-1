# Face Emotion Detection using Deep Learning
This project implements a real-time face emotion recognition system using deep learning in Python. It utilizes a trained Convolutional Neural Network (CNN) to classify human emotions from facial images.

📌 Project Highlights
Real-time emotion detection via webcam or video file

GUI interface built using Tkinter

Emotions detected: Angry, Disgusted, Fearful, Happy, Neutral, Sad, Surprised

Model built using Keras and TensorFlow

Face detection using OpenCV Haarcascade

🧰 Technologies Used
Python

OpenCV

TensorFlow / Keras

NumPy

Tkinter (for GUI)

PIL (for image handling)

smtplib (to send detection results via email)

📁 Files & Folders
model.json – saved model architecture

model_weights.h5 – pre-trained weights

haarcascade_frontalface_default.xml – Haar Cascade face detector

real time project 1.ipynb – main project notebook with code

emotion_detector.py – for real-time detection

requirements.txt – required packages list

🚀 Getting Started
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/face-emotion-detection.git
cd face-emotion-detection
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Ensure you have the model files (model.json, model_weights.h5) and Haar cascade XML file in the working directory.

Run the notebook or main script to start emotion detection.

🖼️ Features
Load and classify emotions from webcam or video files

Email results with attached screenshots

Simple and interactive GUI

Real-time frame updates with emotion labels

🔐 License
This project is open-sourced under the MIT License.

