# NeuralNetwork
Hand Written Digit Classifier from Scratch

Our NN will have a simple two-layer architecture. Input layer  a[0]  will have 784 units corresponding to the 784 pixels in each 28x28 input image. A hidden layer  a[1]  will have 10 units with ReLU activation, and finally our output layer  a[2]  will have 10 units corresponding to the ten digit classes with softmax activation.


### Forward propagation
We can already emphasize one important point which is: the output of one layer is the input of the next one.



### Backward Propagation

As we said, suppose we have a matrix containing the derivative of the error with respect to that layer’s output (∂E/∂Y). We need :

The derivative of the error with respect to the parameters (∂E/∂W, ∂E/∂B)
The derivative of the error with respect to the input (∂E/∂X)


### Gradient Descent
This is a quick reminder, if you need to learn more about gradient descent there are tons of resources on the internet.

Basically, we want to change some parameter in the network (call it w) so that the total error E decreases.
