# mnist

Overview of Dataset

The MNIST database of handwritten digits, available from this page, has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.

It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting.

In machine learning, working with MNIST dataset is equivalent to an "Hello World!" program as in any other programming language.(Not as simple as Hello World but yeah kind of:D)

What the script does

This python script uses TensorFlow library for creating a deep neural network (3 layers).To optimize our cost, I have  used AdamOptimizer, which is a popular optimizer along with others like Stochastic Gradient Descent and AdaGrad, for example. With just about 60 lines of code, it achieves 94-55% accuracy. Even though, this is not the state of the art accuracy, but it only is thing the network is feed is just the pixel values. That's it.
