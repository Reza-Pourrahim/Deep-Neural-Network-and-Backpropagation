# Deep Neural Network and Backpropagation
 In this exercise, we get to have a first hands-on experience with neural network training. Many frameworks (e.g.
PyTorch, Tensor
ow, Caffe) allow easy usage of deep neural networks without precise knowledge on the inner
workings of backpropagation and gradient descent algorithms. While these are very useful tools, it is important
to get a good understanding of how to implement basic network training from scratch, before using this libraries
to speed up the process. For this purpose we will implement a simple two-layer neural network and its training
algorithm based on back-propagation using only basic matrix operations. we also
will use a popular deep learning library, PyTorch, to do the same and understand the advantages offered in
using such tools.
As a benchmark to test our models, we consider an image classiffcation task using the widely used CIFAR-10
dataset. This dataset consists of 50000 training images of 32x32 resolution with 10 object classes, namely
airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks. The task is to code and train a
parameterised model for classifying those images. This involves
 Implementing the feedforward model 
 Implementing the backpropagation algorithm (gradient computation)
 Training the model using stochastic gradient descent and improving the model training with better hyperparameters
 Using the PyTorch Library to implement the above and experiment with deeper networks 
