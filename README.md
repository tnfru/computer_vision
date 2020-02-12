## Digit recognition

My take on the classic MNIST dataset to classify handwritten digits.

I implemented a basic version in pytorch and a way more advanced one in keras.
The keras version hit 0.99614% on kaggle. It uses a slightly changed version of
LeNet5 replacing 5x5 Filter with two 3x3 for non linerarity.

I am using a large number of epochs, but the algorithm checks for overfitting and will abort on its own in the torch version.
