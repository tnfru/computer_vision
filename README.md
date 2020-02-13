# Computer Vision

In this repo I will upload all problem statements I tackled using computer vison. 
I am exectuing these Notebooks on Google Colab, which is a fantastic platform
offering free GPUs and TPUs.
In these I am not using transfer learning as it would basically kill the idea
of learning to design CNN architectures.

## CIFAR

CIFAR10 has been implemented, but will be improved further. CIFAR100 is up next.
Currently my network is at 70% accuracy. I will try to improve it with data 
augmentation and a better network structure.

## MNIST

My take on the classic MNIST dataset to classify handwritten digits.
Current accuracy is at 99.6%. It is unlikely that I am going to improve that.

I implemented it both in torch and keras.
The keras version hit 0.99614 on kaggle. It uses a slightly changed version of
LeNet5 replacing 5x5 Filter with two 3x3 for non linerarity.

I also implemented a basic version in pytorch, which uses a large number of epochs, 
but the algorithm checks for overfitting and will abort on its own. This version
was programmed only on a CPU, hence the small network.
