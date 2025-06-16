# Flower Classification Project - Team 2

A convolutional neural network (CNN) model for classifying flower species using TensorFlow and Keras. This project trains a deep learning model to recognize and classify five different types of flowers from images.

## Overview

This project implements a flower classification system that can identify the following flower species:

* Black-eyed Susan
* Calendula
* California Poppy
* Coreopsis
* Iris

## Features

* **Data Processing**: Automated dataset downloading and organization
* **Data Augmentation**: Image augmentation techniques to improve model strength
* **CNN Architecture**: Custom convolutional neural network with multiple layers
* **Model Training**: Trained model with validation monitoring
* **Visualization**: Training progress visualized with accuracy and loss plots
* **Prediction**: Single image prediction with confidence scores


## Required Dependencies

* TensorFlow
* Kagglehub
* NumPy
* Matplotlib
* PIL (Pillow)

## Dataset

The project uses the "flowers-classification" dataset from Kaggle (seanscully29/flowers-classification). The dataset is automatically downloaded and organized into training and testing sets with a 65/35 split.

## Model Architecture

The CNN model consists of:

* **Convolutional Layers**: 4 Conv2D layers (32, 64, 128, 256 filters)
* **Pooling Layers**: MaxPooling2D after each convolutional layer
* **Dense Layers**: 512-unit fully connected layer + 5-unit output layer
* **Activation**: ReLU for hidden layers, Softmax for output
* **Input Shape**: 150x150x3 (RGB images)

## Usage

## Training the Model

1. **Setup:** The script automatically downloads the dataset and organizes it.
2. **Training:** Run the training process (currently set to 15 epochs)
3. **Model Saving:** The trained model is saved as flower_dataset_model.h5

## Performance

The model is trained for 15 epochs with the following configuration:
* **Optimizer**: Adam
* **Loss Function**: Categorical Crossentropy
* **Metrics**: Accuracy
* **Batch Size**: 32
* **Image Size**: 150x150 pixels

## Getting Started

1. **Environment Setup**: Ensure you have all required packages installed
2. **Run the Script**: Execute the Python file to automatically:
* Download the dataset
* Organize the data
* Train the model
* Generate visualizations
3. **Test Predictions**: Use the prediction function with your own flower images

## Notes

* The project is designed to run in Google Colab environment
* Dataset is automatically downloaded from Kaggle using kagglehub
* Model training time depends on hardware (GPU recommended)
* For better accuracy, consider training for more epochs
* The 65/35 train/test split ensures good model evaluation

## Authored by:
Zender Aurelien-Nikolai, Jammie-Ann Suelina, Sean Scully

# License
* CC0-1.0 Creative Commons