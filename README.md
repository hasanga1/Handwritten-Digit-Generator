
# Handwritten Digit Generator

## Screenshots

**Generated Images for Handwritten Digits MNIST Dataset**

**Generated Images for Fashion MNIST Dataset**
## Introduction

This repository contains a Generative Adversarial Network (GAN) model designed to generate handwritten digits using the MNIST dataset. The GAN consists of a generator and a discriminator, trained to create realistic images of digits.



## Features

- **Generative Adversarial Network (GAN):** The model includes a generator that creates images and a discriminator that evaluates them.

- **Image Generation:** Generates images of handwritten digits (0-9) based on random noise input.
## Dataset

- **Original Dataset:** MNIST dataset containing grayscale images of handwritten digits, 28x28 pixels in size.
- **Alternative Dataset:** You can switch to the Fashion MNIST dataset for generating fashion items images.
- **Image Resolution:** The default model works with 28x28 pixel images. However, you can modify the code to handle different resolutions.
## Changes for Color Images

To adapt the model for generating color images, such as those from a dataset like CIFAR-10, you will need to make the following changes:

- **Dataset:**
    - Change from MNIST (grayscale) to a color image dataset (e.g., CIFAR-10).
    - Update image channels from 1 (grayscale) to 3 (RGB).

- **Image Resolution:**
    - Adjust the model architecture to accommodate larger image sizes (e.g., 32x32 pixels for CIFAR-10).

- **Model Architecture:**
    - Update the generator and discriminator models to handle the new image size and color channels.
    - This requires modifying the convolutional layers to work with the RGB color channels.

- **Hardware Requirements:**
    - Training on color images with higher resolution demands more computational power and memory.
    - Consider using GPUs or cloud-based solutions for efficient training.
## Acknowledgments

- **MNIST Dataset:** [Yann LeCun's MNIST dataset](https://www.github.com/hasanga1)
- **TensorFlow:** [TensorFlow](https://www.github.com/hasanga1) for the deep learning framework.
