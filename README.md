Fashion MNIST Classification with PyTorch
This repository contains code for training a convolutional neural network (CNN) to classify Fashion MNIST dataset using PyTorch.

Dataset
The Fashion MNIST dataset consists of 60,000 training images and 10,000 test images. Each image is a 28x28 grayscale image, associated with a label from 10 classes:

T-shirt/top
Trouser
Pullover
Dress
Coat
Sandal
Shirt
Sneaker
Bag
Ankle boot
Dependencies
PyTorch
NumPy
Matplotlib
Usage
Clone this repository:
git clone https://github.com/your_username/fashion-mnist-classification.git
Install dependencies:
Run the training script:
Evaluate the trained model:
Model Architecture
The neural network architecture consists of several fully connected layers with ReLU activation functions. The model is trained using the cross-entropy loss function and stochastic gradient descent (SGD) optimizer.

Results
The trained model achieved an accuracy of approximately 89.13% on the test dataset.
