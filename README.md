# TNSDC-Generative-AI

## TensorFlow CIFAR-10 Classifier

This is a simple TensorFlow program that demonstrates how to build and train a Convolutional Neural Network (CNN) classifier using the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class.

### Code Overview

The provided code performs the following tasks:

1. **Loading CIFAR-10 Dataset**: Utilizes TensorFlow's built-in CIFAR-10 dataset loader to load the training and testing data.

2. **Data Preprocessing**: Normalizes the pixel values of the images to be between 0 and 1.

3. **Model Architecture**: Defines a CNN model using TensorFlow's Keras API. The model consists of convolutional layers followed by max-pooling layers and fully connected layers.

4. **Model Compilation**: Compiles the model with the Adam optimizer and Sparse Categorical Crossentropy loss function.

5. **Model Training**: Trains the compiled model on the training data for 15 epochs while validating on the test data.

6. **Model Evaluation**: Evaluates the trained model's performance on the test data, computing the test loss and accuracy.

7. **Visualization**: Plots the training and validation accuracy over epochs using Matplotlib.

### How to Use

1. Ensure you have TensorFlow and Matplotlib installed.
   
2. Copy and paste the provided code into a Python script or Jupyter Notebook.

3. Run the script or notebook. The code will automatically download the CIFAR-10 dataset if it's not already downloaded.

4. The script will train the model and display the training/validation accuracy plot.

5. After training, the script will evaluate the model's accuracy on the test data and print the result.

### Requirements

- Python 3.x
- TensorFlow
- Matplotlib

### Credits

This code was adapted from TensorFlow's official documentation and modified for demonstration purposes.
