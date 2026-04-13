😊 EmotionCNN

Real-Time Facial Expression Recognition using Deep Learning (CNN)

🚀 Overview

EmotionCNN is a deep learning-based project that detects human emotions from facial images in real time.
The system uses a Convolutional Neural Network (CNN) to classify facial expressions such as:

👉 Happy | Sad | Angry | Surprise | Fear | Neutral | Disgust

It is designed to work efficiently for real-time applications like AI assistants, surveillance, and mental health analysis.

🎯 Features
🎥 Real-time facial emotion detection
🧠 Deep learning model using CNN
⚡ High accuracy (~98%)
📊 Model evaluation with accuracy & loss graphs
🌐 Web app using Flask
🖼️ Image upload for emotion prediction
🛠️ Tech Stack

Languages:

Python

Libraries & Frameworks:

TensorFlow
Keras
NumPy
Pandas
Matplotlib
scikit-learn
OpenCV / Pillow

Deployment:

Flask
📂 Project Structure
EmotionCNN/
│── app.py
│── model.h5
│── static/
│── templates/
│── uploads/
│── requirements.txt
│── README.md
⚙️ Installation
Clone the repository
git clone https://github.com/your-username/EmotionCNN.git
cd EmotionCNN
Install dependencies
pip install -r requirements.txt
Run the application
python app.py
Open in browser
http://127.0.0.1:5000/
🧪 Model Details
Algorithm: Convolutional Neural Network (CNN)
Dataset: Facial Expression Dataset (FER)
Input Size: 48x48 grayscale images
Output: 7 emotion classes
Accuracy: ~98%
