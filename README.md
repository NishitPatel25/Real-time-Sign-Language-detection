# Real-time Sign Language Detection

This project demonstrates a real-time system for detecting and predicting sign language using LSTM (Long Short-Term Memory) networks and Mediapipe Holistic. The aim is to enable communication through hand gestures, empowering individuals who rely on sign language.

## Features

- **Real-time Detection:** Leverages Mediapipe Holistic for accurate real-time tracking of hand and body landmarks.
- **Sign Prediction:** Uses LSTM-based neural networks to predict the meaning of the detected gestures.
- **User-friendly Interface:** Provides an intuitive interface for smooth interaction.
- **OpenCV for Visualization:** Shows real-time feedback of detected gestures with a visual overlay.

## Technology Stack

- **Mediapipe Holistic:** For real-time hand, body, and face landmark detection.
- **LSTM Neural Network:** For sequence prediction and gesture classification.
- **Keras and TensorFlow:** Backend framework for building and training the LSTM model.
- **OpenCV:** For video capturing and displaying real-time detection results.
- **Python:** The main programming language for the project.

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x
- Mediapipe (`pip install mediapipe`)
- TensorFlow (`pip install tensorflow`)
- Keras (`pip install keras`)
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/sign-language-detection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd sign-language-detection
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Dataset

You will need a dataset of hand gesture images or videos labeled with the corresponding sign language gesture. You can create your own dataset or use a publicly available dataset.

## Usage

- Start the camera feed, and the system will begin detecting hand gestures in real time.
- The LSTM model will classify the detected gestures and display the corresponding predicted sign.
  
## Model Overview

The model consists of:
- **Mediapipe Holistic:** Detects hand landmarks in real time, capturing key features of hand gestures.
- **LSTM Model:** Trained on the sequence of detected landmarks, allowing the system to predict which sign the gesture represents.

## Future Work

- Expand the model to recognize a broader range of gestures.
- Improve model accuracy by adding more training data.
- Implement a web or mobile version of the system.

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

