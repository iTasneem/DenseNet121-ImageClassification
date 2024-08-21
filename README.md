#  DenseNet121-ImageProcessing

 This project implements an image classification model using the DenseNet121 architecture to classify images from the CIFAR-100 dataset.

Table of Contents
Introduction
Dataset
Model Architecture
Installation
Usage
Results
Contributing


Introduction
This repository contains a Jupyter Notebook for performing image classification on the CIFAR-100 dataset using the DenseNet121 model. The CIFAR-100 dataset consists of 100 classes, and the model is trained to classify images into these categories.

Dataset
The CIFAR-100 dataset is used in this project. It contains 60,000 32x32 color images in 100 classes, with 600 images per class. The dataset is split into 50,000 training images and 10,000 testing images.

Model Architecture
The DenseNet121 architecture is utilized for image classification. DenseNet121 is a convolutional neural network model with dense connections between layers, allowing for efficient gradient flow and feature reuse.

The model is fine-tuned for the CIFAR-100 dataset by adding custom layers on top of the base DenseNet121 model.

Installation
To run the code, follow these steps:

Clone the repository

Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Ensure you have Jupyter Notebook installed:

bash
Copy code
pip install notebook
Usage
Open the Jupyter Notebook:

bash
Copy code
jupyter notebook DenseNet121_ImageClassification.ipynb
Follow the steps in the notebook to load the CIFAR-100 dataset, preprocess the data, and train the DenseNet121 model.

Evaluate the model's performance using the test dataset.

Results
The model's performance is evaluated based on accuracy and a classification report. The final classification accuracy on the CIFAR-100 test set is approximately 59%.

Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.
