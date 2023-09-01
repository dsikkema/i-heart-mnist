# Intro
This is not a tutorial, but a plainly-spoken demo of several deep learning concepts and algorithms all in one file and in context. My hope is that if someone was reading one of the many good papers and blogs explaining the forward pass, backpropagation, dropout, learning rate decay, and more, then they would cross reference that with the working implementation shown here without the extra frills and complications that come with seeing an implementation inside a real library.

# How to Use
Run the notebook and read the code comments in it

# What does it do
This notebook downloads the fabled MNIST data set, implements a fully connected neural net from scratch, trains it, then gives you a little widget at the bottom to randomly pick one of the images and see what its predictions are for it.

The implementation is intentionally not object oriented so that the variable names everything looks in-context and tied-together: really great blogs about backprop use the calculus-y names for gradients so I try to respect those in the variable names.

# What things are demonstrated?
* Forward pass ("making inferences")
* Training loop
* Cross entropy loss
* Backpropagation and calculation of gradients
* Cosine learning rate decay
* Dropout
* Try-it-out widget for seeing the model at work
