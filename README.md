# CNN-on-Fashion-MNIST

This project focuses on the development and implementation of a Convolutional Neural Network (CNN) trained on the Fashion MNIST dataset. The objective is to create a model that achieves high accuracy in classifying fashion items.

## Dataset and Model Architecture

The Fashion MNIST dataset, consisting of images representing different fashion items, was used for training and evaluation. A CNN architecture was employed to extract meaningful features from the images and make accurate predictions.

The model architecture includes two hidden layers with 512 nodes each. Multiple activation functions and loss functions were experimented with to optimize the performance of the model. For this particular implementation, the ReLU activation function was utilized, along with the Categorical Cross Entropy loss function.

## Training Parameters

During training, the following parameters were used:

- Learning rate: 0.005
- Batch size: 32
- Epochs: 30

These parameters were chosen to ensure effective learning and convergence of the model.

## Model Performance

The trained model achieved a validation accuracy of 89.11%, indicating its ability to accurately classify fashion items in the test set. Furthermore, the training accuracy reached 95.29%, indicating that the model did not overfit the training data.

