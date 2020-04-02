# Computer Vision

In this repo I will upload all problem statements I tackled using computer vison. 
I am exectuing these Notebooks on Google Colab, which is a fantastic platform
offering free GPUs and TPUs.
In these I am not using transfer learning as it would basically kill the idea
of learning to design CNN architectures.

## CIFAR-10

We use a Wide-ResNet and achieve 93.23% accuracy, beating the original ResNet56v1 
by .2%.
This is due to Dropout and the parallell convolutions in conv and identity modules.

## MNIST

My take on the classic MNIST dataset to classify handwritten digits, which 
achieves 99.6% accuracy.

There are a PyTorch and a Keras implementations in this repository.
The Keras version hit 0.99614 on kaggle. It uses a slightly changed version of
LeNet5 replacing 5x5 Filter with two 3x3 for non linerarity.

The PyTorch implementation, which uses a large number of epochs, 
checks for overfitting and will abort on its own. This version
was programmed only on a CPU, hence the small network.
