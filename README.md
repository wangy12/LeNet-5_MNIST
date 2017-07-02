# CarND-LeNet-Lab


![LeNet-5 Architecture](lenet.png)
Implement the [LeNet-5](http://yann.lecun.com/exdb/lenet/) deep neural network model.

### Steps

* Load the MNIST data
* Preprocess Data
* Setup TensorFlow

| Layer         		|     Description	        					| 
|:---------------------:|:---------------------------------------------:| 
| Input         		| 32x32x1 grayscale image   					| 
| Convolution 5x5     	| 1x1 stride, same padding, outputs 28x28x6 	|
| RELU					| 					|
| Max pooling	      	| 2x2 stride,  outputs 14x14x6 					|
| Convolution 5x5	    | 1x1 stride, same padding, outputs 10x10x16	|
| RELU					| 						|
| Max pooling	      	| 2x2 stride,  outputs 5x5x16 = 400				|
| Fully connected		| outputs 120 									|
| RELU					| 	        									|
| Dropout				| Optional 										|
| Fully connected		| outputs 84									|
| RELU					| 	        									|
| Dropout				| Optional										|
| Fully connected		| outputs 	10								|

* Training and evaluation
