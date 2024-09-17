# Resnet Implementation

This repository contains an implementation of the ResNet (Residual Network) architecture, commonly used for deep learning tasks such as image classification.

## Notebook Overview
The ResNet.ipynb notebook includes:

* __ResNet Architecture__: Demonstrates the construction of a Residual Network using a deep learning framework.
* __Data Preprocessing__: Steps to load and preprocess image data for the model.
* __Training__: Implementation of the training loop, with loss calculation and optimization.
* __Evaluation__: Model performance evaluation using accuracy and loss metrics, with visualizations.
* __Residual Blocks__: Detailed explanation and implementation of residual blocks to address the vanishing gradient problem in deep networks.

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

## Testing with Your Own Data
__To test the model with your own dataset:__

1. Ensure your data is properly pre-processed (resized, normalized) to fit the input shape expected by ResNet.
2. After making these changes, re-run the notebook and observe the model's performance with your data.

## Usage

This notebook provides an end-to-end pipeline for training a ResNet model on image datasets. You can modify and adapt the code to fit your specific use case.






