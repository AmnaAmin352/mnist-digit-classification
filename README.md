# MNIST Digit Classification

A neural network project that classifies handwritten digits (0 to 9) using the MNIST dataset.

## Dataset
Source: MNIST dataset (60,000 training images and 10,000 test images), loaded directly from Keras.

## Tools & Libraries
Python, TensorFlow, Keras, NumPy, Matplotlib, Scikit-learn

## Model Architecture
A fully connected (Dense) neural network:
- Input layer: 784 units (flattened 28x28 pixel images)
- Hidden layer 1: 128 units, ReLU activation
- Hidden layer 2: 64 units, ReLU activation
- Output layer: 10 units, Softmax activation

## Project Workflow
1. Loaded and preprocessed the MNIST dataset
2. Built and trained the neural network for 10 epochs
3. Plotted training and validation accuracy curves
4. Evaluated the model on the test set
5. Generated predictions and a confusion matrix
6. Saved the trained model as mnist_dnn.keras

## Results
Test Accuracy: 97.94%
Test Loss: 0.084

## Files
MNIST.ipynb contains the full workflow including training, evaluation, and predictions.
mnist_dnn.keras is the saved trained model.

## How to Run
1. Clone this repository
2. Install requirements: pip install tensorflow numpy matplotlib scikit-learn
3. Open MNIST.ipynb in Jupyter Notebook and run all cells
