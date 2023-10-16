# IBM Deep Learning with PyTorch Course Project - MNIST CNN

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
     - `CNN` - A simple CNN model.
     - `CNN2` - A more complex CNN model.
   - These models are designed for image classification tasks.

3. **Training and Evaluation**:
   - Training is performed using the training set.
   - The models are evaluated using the validation set to measure accuracy and loss.
   - The project includes functions for training the models and plotting training curves.

## Code Execution

To run the code, follow these steps:

1. Ensure you have the required dependencies installed.

2. Clone this GitHub repository to your local machine.

3. Open and execute the Jupyter Notebook or Python script provided. The main code is available in the notebook, and you can execute code cells to train and evaluate the models.

4. Ensure that you have a compatible GPU available for faster training. The code checks for GPU availability and uses it if found. If no GPU is available, the code will run on the CPU.

5. Execute the code cells in the notebook or run the Python script to train the models. The training process will output training loss and validation accuracy for each epoch.

6. The final training and validation loss, as well as accuracy, will be displayed, and training curves will be plotted to visualize the model's performance.

That's it! You have successfully trained and evaluated CNN models on the MNIST dataset.

For any questions or issues, feel free to contact the project author. Enjoy experimenting with deep learning using PyTorch!

**Note:** This README provides a high-level overview of the project and its code. Detailed code explanations, model architectures, and training results can be found in the accompanying Jupyter Notebook.
