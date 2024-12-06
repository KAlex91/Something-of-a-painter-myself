# I’m Something of a Painter Myself - Simple Monet image style transfer using Pytorch

This is a simple project with the goal of transfering the style of Monet's works of art to any other image. The training data was provided by Kaggle's competition "I'm something of a painter myself".

Objectives

Minimize Content Loss: The difference between the target image and the content image.

Minimize Style Loss: The difference between the Gram matrices of the target image and the style image.

Initialization: In this notebook, the target image is initialized with the content of the content image. By initializing the target image with the content image, we ensure that the target image starts with the correct structural information, making it easier to match the style while retaining the original content.

By balancing these losses, we aim to produce a Target Image that effectively integrates the artistic elements of the Style Image with the recognizable features of the Content Image.
