# Basic Image Classification with TensorFlow

This project demonstrates how to build a basic image classification model using TensorFlow. The model is trained to classify hand-written digits from the MNIST dataset.

## Introduction

The goal of this project is to create and train a model that takes an image of a hand-written digit as input and predicts the class of that digit.

## Dataset

We are using the MNIST dataset, which consists of 60,000 training images and 10,000 test images of hand-written digits (0-9).

## Model Architecture

The model architecture consists of:
- Input layer with 784 nodes (28x28 pixels).
- Two hidden layers with 128 nodes each and ReLU activation.
- Output layer with 10 nodes (one for each digit) and softmax activation.

## Usage

### Requirements

- TensorFlow
- NumPy
- Matplotlib

### Running the Code

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install the required packages:
   ```bash
   pip install tensorflow numpy matplotlib
   ```

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook basic_image_classification.ipynb
   ```

### Example Output

The model achieves an accuracy of approximately 97% on the test set.

### Visualization

The notebook includes code to visualize example predictions and their corresponding ground truth labels.
