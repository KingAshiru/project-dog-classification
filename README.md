# project-doc-classification
Udacity Deep Learning Nano Degree Doc Classification Project

This project uses Python to create a CNN to classify dog breeds from supplied images.

The first part of the implementation is based on a neural network created from scracth with the following architecture:

* 4 convolutional layers increasing the depth from 3 to 128 with batch normalization and max pooling between each layer. These convolutional layers create feature maps of the images.
* 2 hidden linear layers and a linear output layer to classify the detected dog breeds.

The second part uses a pretrained network to peform the feature maps and the trains a linear layer to classify the dog breeds from the images.

## Installation
The simplest way is to install [Anaconda](https://www.anaconda.com/) and start the Jupyter Notebook dog_app.ipyndb.
The supplied setup.sh fil contains command to install some of the required resources, such as the training and validation data. The training was run using the following AMI at Amazon: 

Deep Learning AMI (Ubuntu) Version 20.0 (ami-0827ddd2d8e38aa56)
