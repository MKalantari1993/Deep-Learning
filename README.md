# OCR Model for Reading Persian Car License Plates

## Overview
This project implements an Optical Character Recognition (OCR) model for reading Persian car license plates. The model leverages a combination of Deep Convolutional Neural Networks (CNN), Recurrent Neural Networks (RNN), and Connectionist Temporal Classification (CTC) loss for accurate character recognition.

## Model Architecture
- **Deep CNN:** Utilizes convolutional layers to extract hierarchical features from license plate images.
- **RNN (BiLSTM):** Employs Bidirectional Long Short-Term Memory layers to capture sequential dependencies in character sequences.
- **CTC Loss:** Incorporates Connectionist Temporal Classification loss for training the model to handle variable-length output sequences.

## Usage
The trained model can be used for license plate OCR tasks, providing predictions for characters present on Persian car license plates.

## Dependencies
- TensorFlow
- NumPy
- pandas
- matplotlib


For detailed information, code snippets, and results, refer to the project code.

