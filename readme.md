# Computer Vision and Deep Learning

A collection of computer vision and deep learning experiments exploring image processing, dimensionality reduction, neural network classification, convolutional neural networks and image reconstruction.

The repository focuses on understanding how machine learning models process and learn visual information.

## Projects and Experiments

### 1. Image Processing and PCA Compression
- Loading and displaying images using Pillow
- RGB channel extraction
- Image cropping and pixel manipulation
- Grayscale image processing
- Thresholding and image rotation
- RGB image conversion
- Implementing Principal Component Analysis (PCA) for image compression
- Exploring dimensionality reduction and explained variance

### 2. Handwritten Devanagari Digit Classification
- Loading and preprocessing handwritten digit images
- Resizing and normalising image data
- Building a Multilayer Perceptron (MLP)
- Multi-class classification using Softmax
- Training and evaluating a neural network
- Saving and loading trained models

**Reported test accuracy:** 79.07% in the original notebook.

### 3. Convolutional Neural Networks
- Understanding convolution and pooling operations
- Building CNN architectures using Keras
- Image preprocessing and normalisation
- Model training and validation
- Evaluating classification performance
- Generating classification reports

Experiments include MNIST digit classification and a six-class Amazonian fruit image classification dataset.

**Reported fruit classification test accuracy:** 73.33% in the original notebook.

### 4. Data Augmentation and Transfer Learning
- Image augmentation using random transformations
- Building CNN classification models
- Exploring ResNet50
- Transfer learning using ImageNet-pretrained weights
- Comparing CNN and transfer learning approaches
- Evaluating classification performance

### 5. Denoising Autoencoder
- Understanding encoder-decoder architectures
- Building convolutional autoencoders
- Introducing noise into handwritten digit images
- Training models to reconstruct clean images
- Comparing noisy, reconstructed and original images
- Monitoring training and validation loss

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Pillow
- Scikit-learn

## Repository Structure

```text
computer-vision-deep-learning/
│
├── image-processing-and-pca-compression.ipynb
├── devanagari-digit-classification-mlp.ipynb
├── cnn-image-classification.ipynb
├── data-augmentation-and-resnet50-transfer-learning.ipynb
├── denoising-autoencoder-for-handwritten-digits.ipynb
└── README.md
```

## Learning Objectives

- Understand digital image processing techniques.
- Explore dimensionality reduction using PCA.
- Build and train neural networks for image classification.
- Understand convolutional neural network architectures.
- Experiment with transfer learning and data augmentation.
- Explore unsupervised representation learning through autoencoders.

## Notes on Results

The reported metrics are taken from the original notebooks and have not yet been independently reproduced. Dataset sizes, validation methodology and experimental configurations should be considered when interpreting these results.

## About

This repository documents my practical learning and experimentation in computer vision and deep learning as part of my Artificial Intelligence and Robotics studies.