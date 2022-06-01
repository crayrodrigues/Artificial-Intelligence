CLASSIFICATION USING CONVOLUTIONAL NEURAL NETWORKS. 

#INTRODUCTION
The aim of this project is to used the images from the Fashin MNIST dataset and classify them according to a clothing item. 
10 different types of garments can be presented: T-shirt, trousers, pullover, dress, coat, sandal, shirt, sneaker, bag and ankle boot.  

The open source Machine Learning libray: PyTorch will be used for generating a convolutional neural network that will help us achive our purpose. 

#REQUIREMENTS. 
This module requieres the instalation of different libraries: 
 ·Torchvision
 ·Torchvision.transforms 
 ·Torch
 ·Torch.nn 

All of them have been imported in the first code block. 

#DOWNLOAD.
PyTorch provides an API that will be used to download the training and test Fashion MNIST dataset.
Concretely the function torch.datasets.FashionMNIST() will be used as it is observable in block 2. 

#CONFIGURATION.
Currently the presented code implements the architecture defined in Question 2b) 

For section 2c) 
 ·To change the activation function, the class Classifier(nn.Module) must be modified. The lines corresponding to the ReLU activation function must be commented inside the __init__() function. Additionally the lines regarding to each one of the activation functions must be uncommented. 
 ·To change the values of the learning rates, in block 6, the current opt variable must be commented, and uncomment the line with the required activation function, that are written bellow the commented variable opt. 

For section 2d) Inside the class Classifier(nn.Module), inside the __init__() function we must comment the last line inside the #NEURAL NETWORK WITH ReLU ACTIVATION FUNTION, and uncomment the line that follows #DROPOUT. 