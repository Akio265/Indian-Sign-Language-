# Indian-Sign-Language-
Real-Time Indian Sign Language Recognition This project is a Python-based system for recognizing Indian Sign Language gestures in real-time using a webcam. 
Real-Time Indian Sign Language Recognition
This project is a Python-based system for recognizing Indian Sign Language gestures in real-time using a webcam. It leverages computer vision and machine learning techniques, specifically OpenCV and Mediapipe for hand detection and scikit-learn for gesture classification.

Features
Real-time hand gesture recognition: Detects and classifies 36 gestures (26 alphabets and 10 numerics) using a webcam.
Hand landmark detection: Uses Mediapipe to identify and track hand landmarks.
Machine learning model: Trained using a random forest classifier to recognize gestures.
User interface: Simple interface to start/stop the recognition and display predictions.
Dataset Creation
Tool: OpenCV for capturing video frames and saving them as image files.
Process: Captures images, extracts hand landmarks, and stores them in a dataset for training.
Model Training
Library: Scikit-learn for training a random forest classifier.
Process: Loads dataset, splits data into training and testing sets, trains the model, and evaluates its accuracy.
Real-Time Prediction
Process: Captures live video, detects hand landmarks, extracts features, and predicts gestures in real-time using the trained model.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/Akio265/Indian-Sign-Language.git
Install the required libraries:
bash
Copy code
pip install -r requirements.txt
Usage
Dataset Creation:

Run the script to capture images and create a dataset.
Model Training:

Run the training script to train the random forest classifier on the collected dataset.
Real-Time Recognition:

Run the real-time recognition script to start the webcam and recognize gestures.
Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

License
This project is licensed under the MIT License. See the LICENSE file for details.
