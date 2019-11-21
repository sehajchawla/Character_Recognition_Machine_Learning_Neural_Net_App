# Convolutional Neural Network

This web app uses Python & JavaScript to implement a convolutional neural network built entirely from scratch using only numpy to map out a data set such that any character drawn can be recognised by the model.

Since the app uses no popular dependencies, it gave me a lot of insights into the math behind computational neural nets and intricacies of its optimal use cases.

Using numpy and my learnings from linear algebra and statistics in my university course I implemented everything including gradient descent, dynamic learning rates, convolution, ReLU, and max-pooling. I then passed the modular data through each CNN layer.

This was usually done in the order: convolution, ReLU, max-pooling and then repeated.

The convolution stage is handy in providing some translational invariance, while also ensuring lower computational requirements by allowing small filters to be used. ReLU is used to provide non-linearity to the learning, while max-pooling is extremely useful in providing the bulk of translational and rotational invariance and in reducing computational workload for neuron layers higher up the network.
