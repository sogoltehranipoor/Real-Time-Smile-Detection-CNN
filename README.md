# Real-Time-Smile-Detection-CNN
Real-time smile detection using a Convolutional Neural Network (CNN) and OpenCV. The system detects faces through a webcam and classifies each detected face as Smile or Non-Smile
# Real-Time Smile Detection using CNN

A real-time computer vision project for detecting faces and classifying facial expressions as **Smile** or **Non-Smile** using a Convolutional Neural Network (CNN).

## Project Overview

In this project, a CNN model is trained to classify facial images into two categories:

* Smile
* Non-Smile

After training and saving the model, OpenCV is used to access the webcam and detect faces in real time. Each detected face is passed to the trained CNN model and classified independently.

## Technologies

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Pipeline

Dataset
↓
Image Preprocessing
↓
Train / Test Split
↓
CNN Training
↓
Model Evaluation
↓
Save Trained Model
↓
OpenCV Face Detection
↓
Real-Time Smile Classification

## Real-Time Detection

The webcam application:

1. Captures frames from the webcam.
2. Detects all visible faces using Haar Cascade.
3. Extracts each detected face.
4. Resizes the face to the CNN input size.
5. Normalizes the image.
6. Uses the trained CNN to predict Smile or Non-Smile.
7. Displays the predicted label and confidence score above each face.

Press **Q** to close the webcam.

## Model

The CNN consists of convolutional and pooling layers followed by fully connected layers and a sigmoid output for binary classification.

## Future Improvements

* Improve performance using data augmentation.
* Experiment with transfer learning.
* Improve face detection under different lighting conditions.
* Deploy the model as a web application using Streamlit.
* Evaluate the model using precision, recall, F1-score, and confusion matrix.
