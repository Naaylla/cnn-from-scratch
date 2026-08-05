# CNN From Scratch 

A **Convolutional Neural Network implemented from scratch using NumPy**, without relying on high-level deep learning frameworks such as TensorFlow, Keras or PyTorch.

The goal of this project is to understand how neural networks and CNNs work **at a fundamental level**, by implementing their core mathematical operations manually and visualizing the different stages of the network.

## Objective

Modern deep learning frameworks make it easy to build and train neural networks, but they can hide many of the mathematical operations happening underneath.

This project was developed to explore these mechanisms directly, starting from the fundamentals of a single neuron and progressively building a complete CNN.

The notebook covers:

* Perceptrons and neural network fundamentals
* Forward propagation
* Error computation and backpropagation
* Learning rate and epochs
* Convolution and kernel operations
* Weight sharing and feature extraction
* Pooling
* Fully connected layers
* Activation functions
* Image representation as tensors
* CNN processing on image data

## MNIST Example

The project also includes an example using the **MNIST handwritten digit dataset**.

Images are loaded from CSV files, normalized to the `[0, 1]` range and reshaped into `28 × 28` grayscale images before being processed by the CNN.

The notebook visualizes the different stages of processing, from the original input image to the convolution and final fully connected output.

## Running the Project

Clone the repository:

```bash
git clone https://github.com/Naaylla/cnn-from-scratch.git
cd cnn-from-scratch
```

Install the required dependencies:

```bash
pip install numpy matplotlib jupyter
```

Launch the notebook:

```bash
jupyter notebook cnn_scratch.ipynb
```

Then run the notebook cells sequentially to follow the implementation and visualizations.

## 📚 What I Learned

This project helped me develop a deeper understanding of:

* How neural networks represent and process data
* The mathematical intuition behind forward and backward propagation
* How convolution filters extract visual features
* How pooling affects spatial representations
* How image tensors are transformed throughout a CNN
* How CNN components interact to produce predictions
* The role of weights, biases, activation functions and learning parameters

Rather than treating a CNN as a black box, the project focuses on understanding and implementing the operations that happen **inside the model**.

## 🔗 Repository

[GitHub — CNN From Scratch](https://github.com/Naaylla/cnn-from-scratch)
