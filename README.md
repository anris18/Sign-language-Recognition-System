🖐️ Sign Language Recognition System
A deep-learning-based Sign Language Recognition System that translates hand gestures into text using OpenCV, MediaPipe, and TensorFlow. This system captures real-time hand movements, processes them with a trained LSTM (Long Short-Term Memory) model, and predicts sign language gestures.

📂 Table of Contents
Introduction
Features
Demo
Project Structure
Installation
Dataset Collection
Model Training
Usage
Contributing
License

📖 Introduction
This project aims to bridge communication gaps by translating sign language into readable text using computer vision and deep learning. It utilizes MediaPipe for hand tracking and LSTM networks for gesture recognition.

🚀 Features
✅ Real-time gesture recognition using OpenCV and MediaPipe
✅ LSTM-based deep learning model for accurate predictions
✅ Supports multiple gestures (A, B, C, D, Love)
✅ Custom dataset collection module
✅ Model training and evaluation
✅ Visualization of predictions with probability bars

├── app.py               # Main script for real-time gesture recognition  
├── collectdata.py       # Collects images of hand gestures  
├── data.py              # Prepares data for training  
├── function.py          # Utility functions for hand tracking  
├── trainmodel.py        # Trains the LSTM model  
├── model.json           # JSON representation of trained model  
├── model.h5             # Trained model weights  
├── requirements.txt     # Dependencies  
└── README.md            # Documentation 

⚙️ Installation
1️⃣ Clone the repository
git clone https://github.com/anris18/sign-language-recognition.git
cd sign-language-recognition

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the application
python app.py

📊 Dataset Collection
To collect custom dataset images for training:
python collectdata.py
Press the corresponding key (a, b, c, d, love) to save gesture images.

🛠️ Model Training
Once the dataset is collected, train the model using:
python trainmodel.py
This will create model.json and model.h5, which store the trained model structure and weights.

🖥️ Usage
To start real-time sign language recognition:
python app.py
The system will open a webcam feed and predict gestures in real time.

🤝 Contributing
Contributions are welcome! If you find a bug or want to improve the system:
Fork the repo
Create a new branch
Commit your changes
Open a pull request


