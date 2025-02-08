# MNIST-GAN

This repository contains a **PyTorch implementation** of a **Generative Adversarial Network (GAN)** designed to generate handwritten digit images using the **MNIST** dataset.

## Overview

Generative Adversarial Networks (GANs) consist of two neural networks:
- **Generator:** Learns to create realistic images.
- **Discriminator:** Learns to distinguish between real and fake images.

These two networks are trained simultaneously through adversarial learning, where the generator continuously improves its ability to generate realistic images.

## Features

- **Generator Network:** Uses fully connected layers to generate **28×28** pixel images.
- **Discriminator Network:** Uses fully connected layers to classify images as real or fake.
- **Training Loop:** Includes adversarial training with real and fake data.
- **Visualization:** Generates and displays images after each training epoch.

## Requirements

- Python 3.7+
- PyTorch 1.7+
- torchvision
- matplotlib
- numpy

## Run on Google Colab

To run this model online without installing dependencies, use Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VJ6IaghZrRRhvxJNMnrgCsiZwxqwO7W8?usp=sharing)

Clicking the button above will open the notebook in Google Colab, where you can train the **GAN** model on the **MNIST** dataset. This notebook includes all the necessary steps for downloading the dataset, defining the model, and training it.

## Sample Output (Latest Epoch Image)

After training, the generated image from the last epoch will be something like this:

![Generated Image](https://github.com/SepehrNorouzi7/MNIST-GAN/blob/main/Generated%20Image.png)
