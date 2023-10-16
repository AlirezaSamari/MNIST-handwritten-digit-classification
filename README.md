#Deep Learning with PyTorch Project - MNIST CNN

This repository contains code for a project completed as part of the IBM Deep Learning with PyTorch course. The project focuses on using Convolutional Neural Networks (CNN) to classify the MNIST dataset. This README file provides an overview of the project, its structure, and how to run the code.

## Project Overview

In this project, we implement two different CNN models to classify hand-written digits in the MNIST dataset. We use PyTorch, a popular deep learning framework, for building and training the models. The MNIST dataset consists of 28x28 grayscale images of handwritten digits from 0 to 9. The objective is to create a model that can accurately classify these digits.

## Project Structure

### Prerequisites

Before running the code, make sure you have the following prerequisites installed:

- Python
- PyTorch
- Matplotlib
- NumPy
- pandas

### Code Overview

The project consists of the following main components:

1. **Data Loading and Preprocessing**:
   - We use PyTorch's data loading utilities to download and preprocess the MNIST dataset.
   - The data is divided into training and validation sets.

2. **CNN Model Implementation**:
   - Two different CNN models are implemented, each in its own class:
     - `CNN` - first CNN model.
     - `CNN2` - second CNN model.
   - These models are designed for image classification tasks.

3. **Training and Evaluation**:
   - Training is performed using the training set.
   - The models are evaluated using the validation set to measure accuracy and loss.
   - The project includes functions for training the models and plotting training curves.


**Note:** This README provides a overview of the project and its code. Detailed code explanations, model architectures, and training results can be found in the accompanying Jupyter Notebook.
