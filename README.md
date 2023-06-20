# distributed-ml-applications
Here are some Distributed ML Applications I'm writing and trying by myself, feel free to check them out!

## Applications:

### Project #1:

This project mostly focuses on training a Convolutional Neural Network on the MNIST Dataset with Distributed ML Algorithms. 
The method functions for this purpose are provided by Tensorflow in this project.
I used "Mirrored Strategy" from Tensorflow here. This strategy copies the Model on each device, and performs synchronous training for multiple GPU(s) on one machine.
It creates one replica of the model's variables on each device and updates them synchranously using gradient updates computed on each device. 
