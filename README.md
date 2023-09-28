# CNN_from_scratch_numpy
Welcome to my implementation of a Convolutional Neural Network with only numpy as a matrix operations tool. I really enjoyed working on this, you can even see how my function usage is similar to Pytorch. Here are the implemented classes:

- **Linear**: A linear layer, which performs a weighted sum of its inputs.
- **CrossEntropy**: A cross-entropy loss function, which is commonly used for classification tasks.
- **SGD**: A stochastic gradient descent optimizer, which updates the weights of a neural network in order to minimize the loss function.
- **Adam**: An adaptive moment estimation optimizer, which is a more advanced optimizer than SGD and often performs better.
- **ReLu**: A rectified linear unit activation function, which outputs the maximum of its input and zero.
- **Conv2d**: A convolutional 2D layer, which applies a set of filters to its input and produces a set of feature maps.
- **MaxPool**: A max pooling layer, which reduces the spatial dimensions of its input by taking the maximum value over a window of pixels.

The optimizers also include a weight decay parameter, a momentum parameter, and a nesterov momentum parameter. The model was trained and evaluated on CIFAR10 dataset on CPU. To test the correctness of the implementation, I evaluated the same architecture and parameters with pytorch on GPU. The results were pretty much the same, 60% accuracy after 5 epochs.

This project was only meant to be an exercise for me and I do not intend to further update it. You are welcome to get inspiration from it.