# Image Classification of the CIFAR-10 dataset by a Convolution Neural Networ-CIFAR-10
Build an image classifier by a convolution neural network and perform training/testing in the AWS AMI instance.

## Getting Started
The dataset CIFAR-10 is downloaded into the linux server from  <CIFAR href = "https://www.cs.toronto.edu/~kriz/cifar.html">, unpacked and read into the numpy.array


### Prerequisites

AWS AMI Ubuntu 16.04 with tensorflow, keras pre-installed. 
A jupyter notebook server is configured on the Linux server by the following tutorial from AWS.
<a href = "https://docs.aws.amazon.com/dlami/latest/devguide/tutorial-jupyter.html">

The notebook is opened in the local linux machine and computation is done by the server.

### Training performance with the simple ConvNN can reach ~90% accuracy but the testing performance reaches ~70%. The 20% gap denotes the training dataset has overfit issues.


