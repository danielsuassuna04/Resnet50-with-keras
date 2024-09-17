# Resnet Implementation

This repository contains an implementation of the ResNet (Residual Network) architecture, commonly used for deep learning tasks such as image classification.

## Notebook Overview
The ResNet.ipynb notebook includes:

* ResNet Architecture: Demonstrates the construction of a Residual Network using a deep learning framework.
* Data Preprocessing: Steps to load and preprocess image data for the model.
* Training: Implementation of the training loop, with loss calculation and optimization.
* Evaluation: Model performance evaluation using accuracy and loss metrics, with visualizations.
* Residual Blocks: Detailed explanation and implementation of residual blocks to address the vanishing gradient problem in deep networks.

## Requirements

* Tensorflow

## How to run

1. You can install the necessary packages via pip:

```
pip install tensorflow
```

2. Clone the repository:

```
git clone https://github.com/danielsuassuna04/Resnet50-with-keras.git
```

3. Navigate to the project directory:

```
cd Resnet50-with-keras/
```

4. Start the Jupyter Notebook:

```
jupyter notebook ResNet.ipynb
```

## Applications

* __Image Classification__: Suitable for datasets like CIFAR-10, CIFAR-100, and ImageNet.
* __Object Detection__: ResNet serves as a backbone for many object detection models.
