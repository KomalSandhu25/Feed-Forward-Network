# FeedForwardNetwork

The code files for the Feed Forward Network are private.

The implementation consists of a pipeline of training neural networks to recognize MNIST Handwritten Digits: http://yann.lecun.com/exdb/mnist/.
The feedforward network implementation is done from scratch (using Numpy) without using any in-built python libraries.

The models implemented are 
1. Softmax regression model - composed by a fully-connected layer followed by a ReLU activation.
2. A two-layer multi-layer perceptron (MLP) - two fully-connected layers with a Sigmoid Activation in between.

3. Further, the models are optimized by tweaking the learning rate and regularization.
