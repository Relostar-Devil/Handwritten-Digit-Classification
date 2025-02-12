# Handwritten-Digit-Classification

## Overview
This project implements a convolutional neural network (CNN) for classifying handwritten digits from the MNIST dataset using TensorFlow and Keras. The model learns to distinguish between the digits 0 to 9 through automated feature extraction and achieves high accuracy on unseen data.

## Key Features
- **Data Loading & Preprocessing:**  
  Loads the MNIST dataset directly from TensorFlow, reshapes the images to add a channel dimension, and normalizes pixel values to optimize model training.
  
- **CNN Architecture:**  
  Constructs a neural network comprising a convolutional layer, max pooling, flattening, fully connected (Dense) layers, and dropout to mitigate overfitting.
  
- **Model Training & Evaluation:**  
  Compiles the model with the Adam optimizer and the sparse categorical cross-entropy loss function, trains the network over multiple epochs, and evaluates its performance on the test set.
  
- **Visualization:**  
  Includes code to display sample images alongside their ground truth labels for qualitative assessment, and prints model predictions.

## Results
After training for 3 epochs, the model achieved an evaluation accuracy of around 98.3% on the MNIST test set.
