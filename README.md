# Face Emotion Recognition Web App

A real-time facial emotion recognition web application using a deep learning model. The app detects human emotions such as happy, sad, angry, etc., from facial expressions via webcam or uploaded images.

## 🔍 Features

- Real-time emotion detection using webcam
- Emotion prediction from uploaded images
- Clean UI built with HTML/CSS and JavaScript
- Uses a pre-trained TensorFlow/Keras model (.h5 and .tflite formats)
- Lightweight `.tflite` model for deployment


## 🧠 Model

The models used:
- `unique_face_expression_model_.h5`: Original Keras model.
- `model_quant.tflite`: Quantized version for mobile/web deployment.

## 📂 Project Structure
face_emotion-main/
├── app.py # Flask backend for running the model
├── index.html # Main webpage for webcam input
├── predict.html # Page for image upload predictions
├── script.js # JavaScript for webcam functionality
├── styles.css # Styling for web pages
├── model_quant.tflite # TensorFlow Lite model for emotion recognition
├── unique_face_expression_model_.h5 # Keras model
├── new.ipynb # Notebook for model creation/training
├── test.py # Script for testing model
├── .devcontainer/ # Dev container config
│ └── devcontainer.json
└── README.md # Project documentation


## 📦 Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/amruthayuktha/face_emotion-main.git
    cd face_emotion-main
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the app:
    ```bash
    python app.py
    ```

4. Visit `http://127.0.0.1:5000` in your browser.

## 🛠 Tech Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Flask
- Model: TensorFlow / Keras
- Deployment-ready: TensorFlow Lite

## 📸 Emotion Categories

The model detects multiple facial emotions including:
- Happy
- Sad
- Angry
- Surprise
- Neutral
- Fear
- Disgust

## 🤝 Contributing

Contributions are welcome! Please fork the repo and submit a pull request.
