# Image-Processing

In this, I first load an image as RGB array using PIL library and then input that array to the convolution function and display the output when these 2 kernels are used:\n
kernel1 = [[-1,-1,-1],[-1,8,-1], [-1,-1,-1]] \n
kernel2 = [[0,-1,0], [-1,8,-1],[0,-1,0]] \n
With the first kernel, I get an edge-detected image while with the second kernel I get a sharpened image.

I also built a convolutional network for classification of images in the CIFAR10 image dataset.
