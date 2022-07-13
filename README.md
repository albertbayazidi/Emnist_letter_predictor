# Emnist letter recognition

## Overview  
This is a nootbook containing a simple neural network that was traind on the Emnist letter dataset.


## Usage  
Given a 28x28 image of a letter the program can with 88.635% ± 0.384% accuracy geuess the letter.


## Functionality  
The neural network was built using the PyTorch framwork. It has one hidden layer of size 500, uses leakyReLu as it activation fuction,
and stochastic gradient descent (SGD) as its optimizer. The code can be used with GPU and CPU. With a Google colaboratory account you can borrow a GPU for training, which reduces the time it takes with about 27% deppending on number of epochs   



## Source:  
Cohen, G., Afshar, S., Tapson, J., & van Schaik, A. (2017). EMNIST: an extension of MNIST to handwritten letters. Retrieved from http://arxiv.org/abs/1702.05373
