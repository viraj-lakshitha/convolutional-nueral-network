## Convolutional Neural Network

Convolutional Neural Network is a deep learning neural network which can take an input of image (For an example: AlexNet - 227 x 227 px image). It’s a class of neural networks that specialize in processing data that has a grid-like topology similar to an image.
CNN typically has three layers as convolution layer, pooling layer and fully connected layer.

In the Convolution layer, this layer performs a dot product between two matrices where one layer consists of learnable parameters or kernel and filter that is used to identify the edges of the images.
If we have an image of input of height width of W and filter size of F with stride S and amount of padding P, then the output image size can be calculated using the following formula

![Formulae to find the output](https://miro.medium.com/max/556/1*gRWLLPaarbD3sR-OFeh4mg.png)

The pooling layer replaces the output of the network at certain locations by deriving an average statistic of the outputs. This helps in reducing the spatial size of the representation, and it helps to decrease the required amount of computation and weights. The pooling operation is processed on every slice of the representation individually. 
If we have the activation function of width and height W and pooling kernel size of F and stride S the output image width and height can be calculated by the following formula

![Formulae to find the output](https://miro.medium.com/max/425/1*344e5tcOV5r6emjE6Detug.png)

In the Fully Connected Layer, Neurons in this layer have full connectivity with all neurons in the preceding and succeeding layer as seen in regular FCNN. This is why it can be calculated as usual by a matrix dot multiplication followed by a bias effect. The Fully Connected layer helps to map the representation between the input-output images.
