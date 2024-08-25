

# Image Classification using ResNet-9 on CIFAR-10

This project implements an Image Classification model using ResNet-9 architecture to classify images from the CIFAR-10 dataset. The CIFAR-10 dataset consists of 60,000 32x32 color images across 10 classes, with 6,000 images per class.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project focuses on building a deep learning model for image classification using the ResNet-9 architecture. ResNet-9 is a lightweight version of the ResNet architecture that is suitable for smaller datasets like CIFAR-10. The model achieves high accuracy by leveraging residual connections, which help mitigate the vanishing gradient problem in deep networks.

## Dataset

The CIFAR-10 dataset is a popular benchmark dataset for image classification tasks. It contains 60,000 32x32 color images divided into 10 classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

The dataset is split into 50,000 training images and 10,000 test images.

## Model Architecture

The ResNet-9 architecture used in this project consists of:
- 9 convolutional layers
- Batch normalization
- ReLU activation functions
- Residual connections
- Fully connected layers for classification

This architecture is designed to perform well on small image datasets like CIFAR-10 while maintaining computational efficiency.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/image-classification-resnet9-cifar10.git
    cd image-classification-resnet9-cifar10
    ```


## Results

After training, the model achieves an accuracy of around X% on the CIFAR-10 test set. Below are some example predictions:

| Image         | Predicted Label |
| ------------- | --------------- |
| ![airplane](images/airplane.png) | Airplane        |
| ![cat](images/cat.png)           | Cat             |
| ![truck](images/truck.png)       | Truck           |

## Contributing

Contributions are welcome! If you find any issues or have suggestions, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

