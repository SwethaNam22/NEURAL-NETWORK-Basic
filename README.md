Neural Networks from Scratch: Iris & CIFAR-10 🌱
---------------
For Cifar:
------
CIFAR-10 Dataset 🖼️
CIFAR-10 is a dataset of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The task is to classify each image into one of the 10 classes, such as airplanes, cats, or trucks.

Number of Classes: 10
Image Dimensions: 32x32x3

CIFAR-10 Neural Network 🖼️
For CIFAR-10, the neural network uses a convolutional neural network (CNN) with multiple convolutional layers followed by fully connected layers. The model uses the ReLU activation function and softmax for the final output layer.

-Input Layer: 32x32x3 (image dimensions)
-Conv Layer 1: 32 filters, 3x3 kernel
-Conv Layer 2: 64 filters, 3x3 kernel
-Fully Connected Layer 1: 128 neurons
-Fully Connected Layer 2 (Output): 10 neurons (one for each class)
-->Model Training 🖼️
The model is trained using stochastic gradient descent (SGD). The process includes forward and backward passes through the network, updating the weights at each step.

------------

Future Improvements 🚀
-Using different activation functions like Tanh or Leaky ReLU to analyze their effect on training.
-Implementing batch normalization and dropout to optimize model performance.

