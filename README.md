# Soil-Classification-CNN

A deep learning model using PyTorch and EfficientNet to classify soil into four types: Alluvial, Black, Clay, and Red. Achieves 98.53% test accuracy.

## Soil Classification using Deep Learning

This project uses a Convolutional Neural Network (CNN) to classify soil into four distinct types: Alluvial, Black, Clay, and Red. The model is built with PyTorch and leverages a pre-trained EfficientNet-B0 architecture for transfer learning, achieving a high accuracy of **98.53%** on the test set.

## Table of Contents
* [Dataset](#dataset)
* [Model Architecture](#model-architecture)
* [Installation](#installation)
* [Usage](#usage)
* [Results](#results)

## Dataset

The dataset contains images of four different types of soil:
* Alluvial Soil
* Black Soil
* Clayey Soil
* Red Soil

The data is organized into `train` and `test` directories, with subfolders for each soil type.

## Model Architecture

The model is a `timm/efficientnet-b0` pre-trained on the ImageNet dataset, with the final classification layer modified for our four soil classes. Key components include:

* **Framework:** PyTorch
* **Architecture:** EfficientNet-B0
* **Optimizer:** Adam
* **Loss Function:** Cross-Entropy Loss

## Installation

To run this project, you will need to install the required libraries.

```bash
pip install torch torchvision timm matplotlib pandas jupyter

