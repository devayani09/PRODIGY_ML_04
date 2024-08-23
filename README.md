# PRODIGY_ML_04
**Hand Gesture Recognition using CNN**
This project implements a hand gesture recognition system using Convolutional Neural Networks (CNNs). The model is trained on the LeapGesture dataset, which consists of grayscale images representing different hand gestures. The goal of this project is to enable intuitive human-computer interaction by accurately identifying and classifying various hand gestures.

**Dataset**
Dataset: LeapGesture Recognition
Structure: The dataset is organized into folders 00 to 09, each containing subfolders with images of hand gestures.
Image Details: Each image is in grayscale, representing one of 10 distinct hand gestures.
**Key Steps**
**Data Loading:** Images are loaded from the dataset directories and resized to a uniform size of 64x64 pixels.
**Data Preprocessing:**
Images are normalized to have pixel values between 0 and 1.
Labels are one-hot encoded to prepare them for training.
**Model Architecture:**
The CNN model consists of three convolutional layers followed by max-pooling and batch normalization.
The fully connected layers include dropout regularization to prevent overfitting.
The final layer uses a softmax activation function for multi-class classification.
**Training:**
The model is trained on the preprocessed images with 80% data for training and 20% for validation.
Early stopping is employed to avoid overfitting by monitoring the validation loss.
**Evaluation:**
The model's performance is evaluated using accuracy, classification reports, and confusion matrices.
Training history is visualized to analyze accuracy and loss trends over epochs.
**Saving & Prediction:**
The trained model is saved for future predictions.
Sample predictions are performed to demonstrate the model's capabilities.
**Results**
The model achieved an accuracy of XX% on the test set, demonstrating its effectiveness in recognizing hand gestures.
**Future Work**
Expanding the dataset to include more gestures.
Improving the model's robustness with data augmentation techniques.
Implementing real-time gesture recognition using webcam input.
