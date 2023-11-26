# Neural Style Transfer

This project uses a pre-trained model for neural style transfer. The model architecture is the same as the one specified in the assignment.

## Installation

To run this project, you need to install the following Python libraries:

- TensorFlow
- TensorFlow Hub
- NumPy
- Matplotlib
- PIL

You can install them using pip:

```bash
pip install tensorflow tensorflow-hub numpy matplotlib pillow

```
After installing the libraries, you can run the jupyter notebook.

## Model Architecture

The model architecture is the same as the one specified in the assignment. 

## How it Works

The model uses intermediate layers of a Convolutional Neural Network (CNN) to represent the style and content of the image.

The style of the image is represented using a Gram matrix, which is calculated from the outputs of the intermediate layers of the CNN.

The style transfer algorithm then applies the style of the style image to the content image.(gradient descent with little modification to reduce variance)
