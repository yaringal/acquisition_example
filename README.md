# acquisition_example
Train a simple convnet on the MNIST dataset and evaluate the BALD acquisition function

The acquisition function could then be used for active learning with the images the model is most confused about (highest acquisition function value).

See [Deep Bayesian Active Learning with Image Data](https://arxiv.org/abs/1703.02910).
This code extends on [the Keras CNN example](https://github.com/fchollet/keras/blob/master/examples/mnist_cnn.py).
