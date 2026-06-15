# MNIST Digit Classification

## Overview

This project uses a Neural Network built with TensorFlow and Keras to classify handwritten digits from the MNIST dataset. The workflow includes data preprocessing, model training, regularization techniques, performance evaluation and prediction visualization.

## Dataset

The MNIST dataset contains 70000 grayscale images of handwritten digits ranging from 0 to 9.

* Training samples: 60000
* Test samples: 10000
* Image size: 28 × 28 pixels
* Number of classes: 10

## Data Preparation

The images were flattened from 28 × 28 pixels into 784 input features and normalized to a range between 0 and 1.
Target labels were converted into categorical format using one hot encoding.

## Model Architecture

The model consists of:

* Dense layer with 128 neurons and ReLU activation
* Dense layer with 64 neurons
* Batch Normalization
* ReLU activation
* Dropout layer with a rate of 0.1
* Output layer with 10 neurons and Softmax activation

## Training

The model was trained using the Adam optimizer and categorical cross entropy loss function.

Additional techniques used:

* Early Stopping
* Model Checkpointing
* Validation Split

## Evaluation

Model performance was evaluated using:

* Accuracy
* Loss curves
* Confusion Matrix
* Classification Report

## Results

The trained model achieved approximately 97% test accuracy on the MNIST test dataset.

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Seaborn
* Scikit Learn

## Files

* MNist_Digit_Classification.ipynb
* best_model.keras
* requirements.txt