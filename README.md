# MNIST---binary-classification-problem
Train a deep network to classify MNIST dataset into two classes, deciding whether a digit in the image is greater (or equal to) or less than three (3), i.e. digit >= 3 or digit &lt;3.  

Preprocessing on data:  
1. Downsample the original images to 14 x 14 pixels 
2. Blurring the images.

The network architecture has 1-3 batch-normalized CNN layers (with 3x3xN kernels, where N is an adjustable parameter) and 2x2 strides with zero padding followed by a single fully connected layer. We would like infer how many CNN layers (1, 2 or 3) results in the best performance of the network based on the database we have.
