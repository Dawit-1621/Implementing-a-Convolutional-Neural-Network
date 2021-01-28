# Implementing-a-Convolutional-Neural-Network

## Installation
**Importing Libraries**</br>
* numpy
* pandas
* matplotlib
* sklearn
* tensorflow
* keras

### Instructions:

## Project Motivation
MNIST digit classification <br>
Each image in the MNIST dataset is 28x28 and contains a centered, grayscale digit. Our CNN will take an image and output one of 10 possible classes (one for each digit). <br>
Compiling the Model<br>
Before we can begin training, we need to configure the training process. We decide 3 key factors during the compilation step:<br>

The optimizer. We’ll stick with a pretty good default: the Adam gradient-based optimizer. Keras has many other optimizers you can look into as well.<br>
The loss function. Since we’re using a Softmax output layer, we’ll use the Cross-Entropy loss. Keras distinguishes between binary_crossentropy (2 classes) and categorical_crossentropy (>2 classes), so we’ll use the latter. See all Keras losses.<br>
A list of metrics. Since this is a classification problem, we’ll just have Keras report on the accuracy metric.
## Porject Descriptions 

## Licensing, Authors, Acknowledgements


