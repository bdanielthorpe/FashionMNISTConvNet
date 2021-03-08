# FashionMNISTConvNet
Convolutional neural network trained on Fashion MNIST dataset. Achieves 92% accuracy on test set.

Model uses three convolutional layers of sizes 128, 256, 512 with dropout rate of 0.2 and 2x2 max pooling after each layer. These are followed by a dense layer of size 100 with ReLU activation and dropout rate 0.4. The final layer is softmax.

# Files
* FashionMNISTConvNet.ipynb contains details of preprocessing and training
* model folder contains saved model
