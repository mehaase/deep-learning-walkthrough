# Deep Learning Walkthrough

## Overview

I am following [this
book](http://neuralnetworksanddeeplearning.com/chap1.html), with
modifications to be more Py3k friendly and also to improve readability a bit. I
have also added some visual examples from the MNIST data.

I was struck by the sheer simplicity of this learning approach. There's a lot of
linear algebra and a bit of calculus, so it might not seem *simple* on its face,
but in terms of Python code it's shocking how few lines of code are required to
implement hand writing recognition. The only math dependency is `numpy` for
doing the linear algebra efficiently, so it's not like we're hiding a lot of
machine learning in some other library. The whole thing is right here!

And it works really well! In a few minutes of training on my laptop, the network
has learned to classify digits with 95% accuracy.

## License

This original work and this derivative work are licensed under under a 
[Creative Commons Attribution-NonCommercial 3.0 Unported 
License](https://creativecommons.org/licenses/by-nc/3.0/), which means you are
free to use and modify this code for non-commercial purposes.

## Running

To run these notebooks on your own, you must download the
[mnist.pkl.gz](http://deeplearning.net/data/mnist/mnist.pkl.gz) from the book's
author and place it in the same directory as this notebook. (Do not `gunzip` it
though: this script will decompress on the fly.) You must also `pip3 install -r
requirements.txt`.
