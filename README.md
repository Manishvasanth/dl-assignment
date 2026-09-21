MNIST Handwritten Digit Classification Using TensorFlow

Project Overview

This project uses the MNIST handwritten digit dataset to build a simple neural network using TensorFlow and Keras.

The objective is to classify handwritten digits from 0 to 9.

Dataset

The MNIST dataset contains:

- 60,000 training images
- 10,000 testing images
- Image size: 28 × 28 pixels
- Grayscale images
- 10 classes representing digits 0–9

Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

Model Architecture

The neural network consists of:

1. Flatten layer
2. Dense layer with 128 neurons and ReLU activation
3. Output layer with 10 neurons and Softmax activation

Steps Performed

1. Loaded the MNIST dataset.
2. Explored the dataset.
3. Displayed sample handwritten digit images.
4. Normalized pixel values.
5. Built a neural network using TensorFlow/Keras.
6. Compiled and trained the model.
7. Evaluated the model using test accuracy.
8. Visualized training and validation accuracy.
9. Visualized training and validation loss.
10. Tested five handwritten images.
11. Compared actual and predicted labels.
12. Performed an experiment by changing the hidden layer from 128 neurons to 64 neurons.

Experiment

The original model uses 128 neurons in the hidden layer.

The experimental model uses 64 neurons.

The test accuracy of both models is compared to observe the effect of changing the number of neurons.

Files

- "MNIST_Digit_Classification.ipynb" – Complete Python/Jupyter Notebook
- "MNIST_Report.pdf" – Assignment report
- "mnist_digit_model.keras" – Trained model
- "README.md" – Project documentation

Result

The neural network successfully classifies handwritten digits from 0 to 9 with high test accuracy.

The experiment demonstrates how changing the number of neurons can affect neural network performance.
