# neural-net
A custom neural network implementation that evaluates different architectures, using classes for layers, forward and backward propagation, and custom loss functions

## Techniques Used
- Forward Propagation
- Backward Propagation
- Custom loss functions
- Early Stopping

## Functionality
- Custom Neural Network Implementation
  - The code defines a hierarchy of classes which represent different layers (such as LinearLayer, Sigmoid, Tanh, Softmax) and implement methods for forward and backward propagation  to build a custom neural network
  - The Sequential class is used to build a sequential neural network by adding layers and setting loss functions
  - Custom loss functions (e.g. CrossEntropyLoss) are implemented as subclasses of the Layer class.
- Using the Custom Neural Network
  - The code demonstrates the use of its custom neural network implementation to solve XOR, evaluate different architectures, and train on the MNIST dataset.
  - It creates several sequential neural network models, adds layers (such as LinearLayer, Sigmoid, Tanh) to each model, and sets loss functions.
  - The models are trained using the fit method, which performs forward and backward propagation using the defined layers and loss functions.
  - The training includes early stopping based on validation error.
