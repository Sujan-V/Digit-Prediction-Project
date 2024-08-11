                                       Handwritten Digit Recognition

Overview

This project features two main components:
1. Model Training: A Convolutional Neural Network (CNN) trained on the MNIST dataset to recognize handwritten digits.
2. Interactive Drawing Application: A `pygame` application that allows users to draw digits and predicts them using the trained model.

 Components
- Model Training Script: Trains a CNN on the MNIST dataset and saves the best model.
- Drawing Application: Uses `pygame` to capture user drawings, preprocesses them, and predicts the digit using the trained model.

Requirements
- Python 3.x
- Libraries: `numpy`, `matplotlib`, `keras`, `tensorflow`, `pygame`, `opencv-python`

Installation

Install the required libraries with: pip install numpy matplotlib keras tensorflow pygame opencv-python

Running the Project

1. Train the Model:
   Save and run the model training script:  python train_model.py

2. Run the Drawing Application:
   Save and run the interactive drawing script:   python digit_recognition.py