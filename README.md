# Soil-Classification-CNN
A deep learning model using PyTorch and EfficientNet to classify soil into four types: Alluvial, Black, Clay, and Red. Achieves 98.53% test accuracy.

Soil Classification using Deep Learning
This project uses a Convolutional Neural Network (CNN) to classify soil into four distinct types: Alluvial, Black, Clay, and Red. The model is built with PyTorch and leverages a pre-trained EfficientNet-B0 architecture for transfer learning, achieving a high accuracy of 98.53% on the test set.

Table of Contents
Dataset

Model Architecture

Installation

Usage

Results

Contributing

Dataset
The dataset contains images of four different types of soil:

Alluvial Soil

Black Soil

Clayey Soil

Red Soil

The data is organized into train and test directories, with subfolders for each soil type.

Model Architecture
The model is a timm/efficientnet-b0 pre-trained on the ImageNet dataset, with the final classification layer modified for our four soil classes. Key components include:

Framework: PyTorch

Architecture: EfficientNet-B0

Optimizer: Adam

Loss Function: Cross-Entropy Loss

Installation
To run this project, you'll need to install the following libraries. You can install them using pip:

Bash

pip install torch torchvision timm matplotlib pandas
Usage
Clone the repository:

Bash

git clone https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository
Navigate to the project directory:

Bash

cd [repository-name]
Run the Jupyter Notebook:
Open and run the soil_classification.ipynb notebook in a Jupyter environment. The notebook covers:

Data loading and preprocessing.

Model definition and training.

Evaluation and visualization of results.

Results
The model achieved the following performance on the test set:

Accuracy: 98.53%

Loss: [Add your final loss value here]

Here is the confusion matrix from the model's predictions:

(You can add a screenshot of your confusion matrix here if you like)
