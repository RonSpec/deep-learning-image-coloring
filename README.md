# Image Colorization Using GANs

This project focuses on the task of image colorization using Generative Adversarial Networks (GANs). The model is built using a U-Net based generator and a discriminator network, designed to convert grayscale images into colorized versions. The dataset used for training consists of flower images.

## Overview

The repository contains the implementation of a GAN-based model for colorizing grayscale images. The key components include:

- **U-Net Generator**: Handles the transformation of grayscale images to color.
- **Discriminator**: Evaluates the quality and realism of the generated color images.
- **Training Pipeline**: Manages data preprocessing, model training, and performance evaluation.

## Features

- **Advanced U-Net Architecture**: Adapted for effective image colorization.
- **Discriminative Training**: Ensures high-quality and realistic color outputs.
- **End-to-End Pipeline**: From data loading to model evaluation.

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow or PyTorch
- Other necessary libraries (listed in `requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/RonSpec/deep-learning-image-coloring.git
   ```
2. Navigate to the project directory:
   ```bash
   cd deep-learning-image-coloring
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Prepare your dataset of grayscale images, avaliable in the following link:
   ```bash
   https://www.robots.ox.ac.uk/~vgg/data/flowers/102/102flowers.tgz
   ```
2. Change the value of `FLOWER_PATH` in the following line of code (found in the 3rd cell):
![image](https://github.com/user-attachments/assets/16b9f6d0-4022-4bef-848b-c5b19cb25ce7)

3. Procceed to run the code.

### Results

The model generates colorized versions of grayscale images with promising results. Sample outputs and evaluation metrics can be found in the notebook.

## Contributing

Contributions are welcome! Please fork the repository, create a branch for your feature or bug fix, and submit a pull request.

## Acknowledgments

- [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
- [GANs: Generative Adversarial Networks](https://arxiv.org/abs/1406.2661)
